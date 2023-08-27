---
title: "Final Report"
description: ""
lead: ""
date: 2023-08-22T20:09:13+05:00
lastmod: 2023-08-22T20:09:13+05:00
draft: false
images: []
menu:
  docs:
    parent: "r"
    identifier: "final-report-a0e729093563de47c17546329c7e65da"
weight: 1
toc: true
type: docs
---


![GCCRS Logo](gccrs-logo.png)

## Enhancing user errors & Error Code Support for GCC Rust (GCCRS) Frontend
- Organization: [GNU Compiler Collection (GCC)](https://gcc.gnu.org/)
- Mentors: [Philip Herron](https://github.com/philberty/), [Arthur Cohen](https://github.com/cohenarthur/)
---
## Description:
The goal of this project is to enhance the user experience of gnu gccrs by introducing and implementing error codes that are compatible with rustc. This will facilitate the integration of the two test suites and enable the rustc testsuite to run on gccrs. The project will require modifying the gccrs frontend code to generate more informative error messages and rich locations to assist users and developers in improving their code.

---

## What was done:

- [x] Restructured the `ErrorCode` struct into an `enum` class, alongside the respective functions like `make_description` and `make_url`. This modification was carried out to enforce accurate error codes and establish an API for emitting error codes.
   - [x] Updated & refactored the error handling code to use the new error code framework.
   - [x]Addressed a prevailing memory leak that was present in the previous error code framework.
- [x] Enhanced the Error struct's functionality to encompass storage of error codes and locations. This was used as a wrapper function to store and emit error codes specifically tailored for parsing and expansion errors.
- [x] Modified error handling code to use `rich locations`, which offer more details about the error location and help users and developers to improve their code.
- [x] Refined error messages to be more user-friendly and informative.
- [x] Conducted a comprehensive comparison between the rustc test suite and gccrs, resulting in the identification and rectification of several issues, including bugs and internal compiler errors. This iterative process led to substantial improvements in the gccrs stability. The detailed analysis is available on dedicated [comparison page](https://mahadmuhammad.github.io/gsoc/23/r/relative-to-rustc/).

---

## Previous & Current state:

In a prior development phase, [David Malcolm](https://github.com/davidmalcolm) extended the capabilities of GCC diagnostics to incorporate support for associating diagnostics with rules from coding standards. We are using this feature to associate gcc-rust error codes. The initial introduction included a solitary error, denoted as [E0054](https://doc.rust-lang.org/error_codes/E0054.html) , addressing non-allowed cast operations to bool. Following the integration of further type-checking mechanisms, gccrs commenced emitting error codes and messages that closely resembled those of rustc.

```rust
fn main() {
    let x = 5;
    let x_is_nonzero = x as bool; // { dg-error "cannot cast .<integer>. as .bool." }

    0u32 as char; // { dg-error "cannot cast .u32. as .char., only .u8. can be cast as .char." }

    let x = &[1_usize, 2] as [usize]; // { dg-error "cast to unsized type: .& .usize:CAPACITY.. as ..usize.." }

    let a = &0u8; // Here, `x` is a `&u8`.
    let y: u32 = a as u32; // { dg-error "casting .& u8. as .u32. is invalid" }
}
```
### Previous State:
The previous version exhibited the following output:
```bash
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:3:24: error: invalid cast ‘<integer>’ to ‘bool’ [E0054]
    3 |     let x_is_nonzero = x as bool; // { dg-error "cannot cast .<integer>. as .bool." }
      |                        ^    ~~~~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:5:5: error:invalid cast ‘u32’ to ‘char’ [E0054]
    5 |     0u32 as char; // { dg-error "cannot cast .u32. as .char., only .u8. can be cast as .char." }
      |     ^~~~    ~~~~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:7:13: error: invalid cast ‘& [usize:CAPACITY]’ to ‘[usize]’ [E0054]
    7 |     let x = &[1_usize, 2] as [usize]; // { dg-error "cast to unsized type: .& .usize:CAPACITY.. as ..usize.." }
      |             ^                ~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:10:18: error: invalid cast ‘& u8’ to ‘u32’ [E0054]
   10 |     let y: u32 = a as u32; // { dg-error "casting .& u8. as .u32. is invalid" }
      |                  ^    ~~~
```
### Current State:
With the incorporation of the latest type checking code, the system now emits more specific error codes and associated error messages.

```bash
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:3:24: error: cannot cast ‘<integer>’ as ‘bool’ [E0054]
    3 |     let x_is_nonzero = x as bool; // { dg-error "cannot cast .<integer>. as .bool." }
      |                        ^    ~~~~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:5:5: error: cannot cast ‘u32’ as ‘char’, only ‘u8’ can be cast as ‘char’ [E0604]
    5 |     0u32 as char; // { dg-error "cannot cast .u32. as .char., only .u8. can be cast as .char." }
      |     ^~~~    ~~~~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:7:13: error: cast to unsized type: ‘& [usize:CAPACITY]’ as ‘[usize]’ [E0620]
    7 |     let x = &[1_usize, 2] as [usize]; // { dg-error "cast to unsized type: .& .usize:CAPACITY.. as ..usize.." }
      |             ^                ~
~/gccrs/gcc/testsuite/rust/compile/all-cast.rs:10:18: error: casting ‘& u8’ as ‘u32’ is invalid [E0606]
   10 |     let y: u32 = a as u32; // { dg-error "casting .& u8. as .u32. is invalid" }
      |                  ^    ~~~
```

## Bugs Finding:
A comprehensive compilation of the bugs I discovered is available on the dedicated [bugs page](https://mahadmuhammad.github.io/gsoc/23/r/issues/). Among these, here are several intriguing bugs captured my attention and were successfully resolved over the course of my project:
### ICE with return expression outside of context:
One of the intriguing bugs uncovered during the investigation of error codes in gccrs pertained to an `internal compiler error - ICE`. Specifically, gccrs encountered issues when attempting to access an empty stack, which not only posed a security concern but was also not permitted in rustc. This issue has now been addressed, resulting in the proper emission of error codes and messages, aligning with the behavior in rustc.
```rust
const FOO: u32 = return 0; 
```
Previously, this triggered an error causing an internal compiler error. Now, the issue is rectified, and gccrs emits the appropriate error code and message, in line with rustc's behavior.
```bash
empty-stack.rs:1:18: error: return statement outside of function body [E0572]
    1 | const FOO: u32 = return 0; // error: return statement outside of function body
      |                  ^~~~~~
```
### Resolve type path error:
I raised an issue that played a pivotal role in identifying and addressing an issue that contributed to enabling proper support for `?Sized` and `Sized` trait bounds within the gccrs. This issue was subsequently resolved by my mentor.
## Contributions Overview:
### Pull Requests:
For a comprehensive overview of the pull requests I've submitted, visit [pull requests page](https://mahadmuhammad.github.io/gsoc/23/r/pulls/). Alternatively, you can also view the pull requests I've initiated on [GitHub](https://github.com/Rust-GCC/gccrs/pulls?q=is%3Apr+author%3AMahadMuhammad+created%3A%3C%3D2023-09-10+) and on this [tracking issue](https://github.com/Rust-GCC/gccrs/issues/2553).

### Issues:
To delve deeper into the intricacies of the issues I've engaged with, feel free to explore the dedicated [issue page](https://mahadmuhammad.github.io/gsoc/23/r/issues/). Furthermore, you can also explore the issues I've raised, all viewable on [GitHub](https://github.com/Rust-GCC/gccrs/issues?q=is%3Aissue+author%3AMahadMuhammad+created%3A%3C%3D2023-09-10+) and also on this [tracking issue](https://github.com/Rust-GCC/gccrs/issues/2553).

## Learning Journey:

### Gained Insights:
- The most significant skill I acquired involved navigating extensive C++ codebases. It was my inaugural experience with such immense code complexity. 
  - Moreover, I delved into the intricacies of compiler internals, unveiling operational nuances beyond the scope of conventional academic compiler courses.
- Mastered effective communication and collaborative problem-solving. Despite my initial apprehension towards English communication, the unwavering support and encouragement from my mentors facilitated a transformative shift, enabling me to overcome this fear and communicate more confidently.
- Embraced a paradigm shift: Prioritizing progress over perfection. A sage piece of advice from my mentor, [Philip Herron](https://github.com/philberty/), catalyzed my work approach.
- Leveraged automation for productivity enhancement and error reduction:
  - Utilized [Python-driven](https://gist.github.com/MahadMuhammad/8c9d5fc88ea18d8c520937a8071d4185#file-rustc-errorcode-parser-py) automation to validate error codes and messages. This approach streamlined the process, obviating manual effort and minimizing error risks.
- Honed time and project management adeptness using versatile tools, notably [GitHub Projects](https://github.com/users/MahadMuhammad/projects/7/views/1) 
### Overcoming Challenges:

In my initial attempts, I encountered difficulty in successfully passing the evaluations carried out by the CI/CD system. In this context, my mentor [Arthur Cohen](https://github.com/cohenarthur/) guided me to pass the CI/CD. Moreover, during this collaborative effort, we uncovered a weakness within the current CI/CD framework, highlighted in this particular issue: [CI fails if test file contains the word "unexpected" or "unresolved" #2386](https://github.com/Rust-GCC/gccrs/issues/2386).

## Work for the future:
- Expanding the range of error codes and messages to cover more scenarios.
- Updating the error handling code for the existing error codes to incorporate `rich locations`, which offer more details about the error location, and facilitate users and developers to debug and enhance their code.
- Fixing the ICE issues that are still present in the current version of gccrs.

## Acknowledgements:
I am very grateful to the following people who made this project possible and supported me throughout the process. Their expertise, feedback and encouragement were invaluable for me. 
- [Philip Herron](https://github.com/philberty/) & [Arthur Cohen](https://github.com/cohenarthur/) for being my amazing mentors and guiding me with their insights and experience.
- [Pierre Emmanuel Patry](https://github.com/P-E-P/) for reviewing my code and giving me helpful suggestions. Also, [Marc Poulhiès](https://github.com/dkm), [Thomas Schwinge](https://github.com/tschwinge), [Philipp Krones](https://github.com/flip1995/) for sharing their knowledge and tips with me.
- And last but not least, [Faisal Abbas](https://github.com/abbasfaisal/) for assisting me in my initial contributions and helping me with my proposal.