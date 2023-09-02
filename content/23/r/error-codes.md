---
title: "Error Codes"
description: ""
lead: ""
date: 2023-08-23T01:05:29+05:00
lastmod: 2023-08-23T01:05:29+05:00
draft: false
images: []
menu:
  docs:
    parent: "r"
    identifier: "error-codes-37f6d2f77a95524d75f13d54e7b04d13"
weight: 4
toc: true
type: docs
---

Currently, there are total 506 ErrorCodes, which are present in the rustc error codes [directory](https://github.com/rust-lang/rust/tree/master/compiler/rustc_error_codes/src/error_codes/), but only 438 we offically emitted by the rustc compiler. Here's the detailed list of all the error codes, which are emitted by rustc and which are not. 

---

## Error Codes no longer emitted by rustc:

[`E0001`](https://doc.rust-lang.org/error_codes/E0001.html)
[`E0002`](https://doc.rust-lang.org/error_codes/E0002.html)
[`E0007`](https://doc.rust-lang.org/error_codes/E0007.html)
[`E0009`](https://doc.rust-lang.org/error_codes/E0009.html)
[`E0014`](https://doc.rust-lang.org/error_codes/E0014.html)
[`E0073`](https://doc.rust-lang.org/error_codes/E0073.html)
[`E0074`](https://doc.rust-lang.org/error_codes/E0074.html)
[`E0087`](https://doc.rust-lang.org/error_codes/E0087.html)
[`E0088`](https://doc.rust-lang.org/error_codes/E0088.html)
[`E0089`](https://doc.rust-lang.org/error_codes/E0089.html)
[`E0090`](https://doc.rust-lang.org/error_codes/E0090.html)
[`E0110`](https://doc.rust-lang.org/error_codes/E0110.html)
[`E0136`](https://doc.rust-lang.org/error_codes/E0136.html)
[`E0137`](https://doc.rust-lang.org/error_codes/E0137.html)
[`E0139`](https://doc.rust-lang.org/error_codes/E0139.html)
[`E0154`](https://doc.rust-lang.org/error_codes/E0154.html)
[`E0162`](https://doc.rust-lang.org/error_codes/E0162.html)
[`E0165`](https://doc.rust-lang.org/error_codes/E0165.html)
[`E0192`](https://doc.rust-lang.org/error_codes/E0192.html)
[`E0193`](https://doc.rust-lang.org/error_codes/E0193.html)
[`E0205`](https://doc.rust-lang.org/error_codes/E0205.html)
[`E0208`](https://doc.rust-lang.org/error_codes/E0208.html)
[`E0211`](https://doc.rust-lang.org/error_codes/E0211.html)
[`E0243`](https://doc.rust-lang.org/error_codes/E0243.html)
[`E0244`](https://doc.rust-lang.org/error_codes/E0244.html)
[`E0251`](https://doc.rust-lang.org/error_codes/E0251.html)
[`E0256`](https://doc.rust-lang.org/error_codes/E0256.html)
[`E0263`](https://doc.rust-lang.org/error_codes/E0263.html)
[`E0281`](https://doc.rust-lang.org/error_codes/E0281.html)
[`E0297`](https://doc.rust-lang.org/error_codes/E0297.html)
[`E0301`](https://doc.rust-lang.org/error_codes/E0301.html)
[`E0302`](https://doc.rust-lang.org/error_codes/E0302.html)
[`E0303`](https://doc.rust-lang.org/error_codes/E0303.html)
[`E0312`](https://doc.rust-lang.org/error_codes/E0312.html)
[`E0329`](https://doc.rust-lang.org/error_codes/E0329.html)
[`E0383`](https://doc.rust-lang.org/error_codes/E0383.html)
[`E0386`](https://doc.rust-lang.org/error_codes/E0386.html)
[`E0387`](https://doc.rust-lang.org/error_codes/E0387.html)
[`E0388`](https://doc.rust-lang.org/error_codes/E0388.html)
[`E0389`](https://doc.rust-lang.org/error_codes/E0389.html)
[`E0398`](https://doc.rust-lang.org/error_codes/E0398.html)
[`E0439`](https://doc.rust-lang.org/error_codes/E0439.html)
[`E0447`](https://doc.rust-lang.org/error_codes/E0447.html)
[`E0448`](https://doc.rust-lang.org/error_codes/E0448.html)
[`E0477`](https://doc.rust-lang.org/error_codes/E0477.html)
[`E0482`](https://doc.rust-lang.org/error_codes/E0482.html)
[`E0495`](https://doc.rust-lang.org/error_codes/E0495.html)
[`E0497`](https://doc.rust-lang.org/error_codes/E0497.html)
[`E0504`](https://doc.rust-lang.org/error_codes/E0504.html)
[`E0523`](https://doc.rust-lang.org/error_codes/E0523.html)
[`E0595`](https://doc.rust-lang.org/error_codes/E0595.html)
[`E0619`](https://doc.rust-lang.org/error_codes/E0619.html)
[`E0632`](https://doc.rust-lang.org/error_codes/E0632.html)
[`E0633`](https://doc.rust-lang.org/error_codes/E0633.html)
[`E0660`](https://doc.rust-lang.org/error_codes/E0660.html)
[`E0661`](https://doc.rust-lang.org/error_codes/E0661.html)
[`E0662`](https://doc.rust-lang.org/error_codes/E0662.html)
[`E0663`](https://doc.rust-lang.org/error_codes/E0663.html)
[`E0664`](https://doc.rust-lang.org/error_codes/E0664.html)
[`E0665`](https://doc.rust-lang.org/error_codes/E0665.html)
[`E0668`](https://doc.rust-lang.org/error_codes/E0668.html)
[`E0669`](https://doc.rust-lang.org/error_codes/E0669.html)
[`E0671`](https://doc.rust-lang.org/error_codes/E0671.html)
[`E0687`](https://doc.rust-lang.org/error_codes/E0687.html)
[`E0688`](https://doc.rust-lang.org/error_codes/E0688.html)
[`E0759`](https://doc.rust-lang.org/error_codes/E0759.html)
[`E0760`](https://doc.rust-lang.org/error_codes/E0760.html)
[`E0772`](https://doc.rust-lang.org/error_codes/E0772.html)

---

## Error Codes emitted by rustc:

Here, is the detailed description of all the error codes which are emitted by emitted by rustc and their support in gccrs. See this [`gist`](https://gist.github.com/MahadMuhammad/8c9d5fc88ea18d8c520937a8071d4185) for more detail. Also, see this tracking issue on GitHub, [here](https://github.com/Rust-GCC/gccrs/issues/2553)

- [ ] [`E0004`](https://doc.rust-lang.org/error_codes/E0004.html)
  - **Error Description:** This error indicates that the compiler cannot guarantee a matching pattern for
one or more possible inputs to a match expression. Guaranteed matches are
required in order to assign values to match expressions, or alternatively,
determine the flow of execution.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2311
- [ ] [`E0005`](https://doc.rust-lang.org/error_codes/E0005.html)
  - **Error Description:** Patterns used to bind names must be irrefutable, that is, they must guarantee
that a name will be extracted in all cases.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2508
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2509
- [ ] [`E0010`](https://doc.rust-lang.org/error_codes/E0010.html)
  - **Error Description:** The value of statics and constants must be known at compile time, and they live
for the entire lifetime of a program. Creating a boxed value allocates memory on
the heap at runtime, and therefore cannot be done at compile time.
- [ ] [`E0013`](https://doc.rust-lang.org/error_codes/E0013.html)
  - **Error Description:** Static and const variables can refer to other const variables. But a const
variable cannot refer to a static variable.
- [x] [`E0015`](https://doc.rust-lang.org/error_codes/E0015.html)
  - **Error Description:** A non-`const` function was called in a `const` context.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2538
- [x] [`E0023`](https://doc.rust-lang.org/error_codes/E0023.html)
  - **Error Description:** A pattern attempted to extract an incorrect number of fields from a variant.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2325
- [ ] [`E0025`](https://doc.rust-lang.org/error_codes/E0025.html)
  - **Error Description:** Each field of a struct can only be bound once in a pattern.
- [x] [`E0026`](https://doc.rust-lang.org/error_codes/E0026.html)
  - **Error Description:** A struct pattern attempted to extract a nonexistent field from a struct.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2326
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2336
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2341
- [x] [`E0027`](https://doc.rust-lang.org/error_codes/E0027.html)
  - **Error Description:** A pattern for a struct fails to specify a sub-pattern for every one of the
struct's fields.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2335
- [ ] [`E0029`](https://doc.rust-lang.org/error_codes/E0029.html)
  - **Error Description:** Something other than numbers and characters has been used for a range.
- [ ] [`E0030`](https://doc.rust-lang.org/error_codes/E0030.html)
  - **Error Description:** When matching against a range, the compiler verifies that the range is
non-empty. Range patterns include both end-points, so this is equivalent to
requiring the start of the range to be less than or equal to the end of the
range.
- [ ] [`E0033`](https://doc.rust-lang.org/error_codes/E0033.html)
  - **Error Description:** A trait type has been dereferenced.
- [x] [`E0034`](https://doc.rust-lang.org/error_codes/E0034.html)
  - **Error Description:** The compiler doesn't know what method to call because more than one method
has the same prototype.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2366
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2365
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2560  
- [ ] [`E0038`](https://doc.rust-lang.org/error_codes/E0038.html)
  - **Error Description:** For any given trait `Trait` there may be a related _type_ called the _trait
object type_ which is typically written as `dyn Trait`. In earlier editions of
Rust, trait object types were written as plain `Trait` (just the name of the
trait, written in type positions) but this was a bit too confusing, so we now
write `dyn Trait`.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2375
- [ ] [`E0040`](https://doc.rust-lang.org/error_codes/E0040.html)
  - **Error Description:** It is not allowed to manually call destructors in Rust.
- [ ] [`E0044`](https://doc.rust-lang.org/error_codes/E0044.html)
  - **Error Description:** You cannot use type or const parameters on foreign items.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2376
- [x] [`E0045`](https://doc.rust-lang.org/error_codes/E0045.html)
  - **Error Description:** Variadic parameters have been used on a non-C ABI function.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2382
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2451
- [x] [`E0046`](https://doc.rust-lang.org/error_codes/E0046.html)
  - **Error Description:** Items are missing in a trait implementation.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2377
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2378
- [ ] [`E0049`](https://doc.rust-lang.org/error_codes/E0049.html)
  - **Error Description:** An attempted implementation of a trait method has the wrong number of type or
const parameters.
- [ ] [`E0050`](https://doc.rust-lang.org/error_codes/E0050.html)
  - **Error Description:** An attempted implementation of a trait method has the wrong number of function
parameters.
- [x] [`E0053`](https://doc.rust-lang.org/error_codes/E0053.html)
  - **Error Description:** The parameters of any trait method must match between a trait implementation
and the trait definition.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2380
- [x] [`E0054`](https://doc.rust-lang.org/error_codes/E0054.html)
  - **Error Description:** It is not allowed to cast to a bool.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2528
- [ ] [`E0055`](https://doc.rust-lang.org/error_codes/E0055.html)
  - **Error Description:** During a method call, a value is automatically dereferenced as many times as
needed to make the value's type match the method's receiver. The catch is that
the compiler will only attempt to dereference a number of times up to the
recursion limit (which can be set via the `recursion_limit` attribute).
- [ ] [`E0057`](https://doc.rust-lang.org/error_codes/E0057.html)
  - **Error Description:** An invalid number of arguments was given when calling a closure.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2384
- [ ] [`E0059`](https://doc.rust-lang.org/error_codes/E0059.html)
  - **Error Description:** The built-in function traits are generic over a tuple of the function arguments.
If one uses angle-bracket notation (`Fn<(T,), Output=U>`) instead of parentheses
(`Fn(T) -> U`) to denote the function trait, the type parameter should be a
tuple. Otherwise function call notation cannot be used and the trait will not be
implemented by closures.
- [ ] [`E0060`](https://doc.rust-lang.org/error_codes/E0060.html)
  - **Error Description:** External C functions are allowed to be variadic. However, a variadic function
takes a minimum number of arguments. For example, consider C's variadic `printf`
function:
- [x] [`E0061`](https://doc.rust-lang.org/error_codes/E0061.html)
  - **Error Description:** An invalid number of arguments was passed when calling a function.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2373
- [ ] [`E0062`](https://doc.rust-lang.org/error_codes/E0062.html)
  - **Error Description:** A struct's or struct-like enum variant's field was specified more than once.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2381
- [x] [`E0063`](https://doc.rust-lang.org/error_codes/E0063.html)
  - **Error Description:** A struct's or struct-like enum variant's field was not provided.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2387
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2388
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2389
- [ ] [`E0067`](https://doc.rust-lang.org/error_codes/E0067.html)
  - **Error Description:** An invalid left-hand side expression was used on an assignment operation.
- [ ] [`E0069`](https://doc.rust-lang.org/error_codes/E0069.html)
  - **Error Description:** The compiler found a function whose body contains a `return;` statement but
whose return type is not `()`.
- [x] [`E0070`](https://doc.rust-lang.org/error_codes/E0070.html)
  - **Error Description:** An assignment operator was used on a non-place expression.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2390
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2391
- [ ] [`E0071`](https://doc.rust-lang.org/error_codes/E0071.html)
  - **Error Description:** A structure-literal syntax was used to create an item that is not a structure
or enum variant.
- [ ] [`E0072`](https://doc.rust-lang.org/error_codes/E0072.html)
  - **Error Description:** A recursive type has infinite size because it doesn't have an indirection.
- [ ] [`E0075`](https://doc.rust-lang.org/error_codes/E0075.html)
  - **Error Description:** A `#[simd]` attribute was applied to an empty tuple struct.
- [ ] [`E0076`](https://doc.rust-lang.org/error_codes/E0076.html)
  - **Error Description:** All types in a tuple struct aren't the same when using the `#[simd]`
attribute.
- [ ] [`E0077`](https://doc.rust-lang.org/error_codes/E0077.html)
  - **Error Description:** A tuple struct's element isn't a machine type when using the `#[simd]`
attribute.
- [ ] [`E0080`](https://doc.rust-lang.org/error_codes/E0080.html)
  - **Error Description:** A constant value failed to get evaluated.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2394
- [ ] [`E0081`](https://doc.rust-lang.org/error_codes/E0081.html)
  - **Error Description:** A discriminant value is present more than once.
- [ ] [`E0084`](https://doc.rust-lang.org/error_codes/E0084.html)
  - **Error Description:** An unsupported representation was attempted on a zero-variant enum.
- [ ] [`E0091`](https://doc.rust-lang.org/error_codes/E0091.html)
  - **Error Description:** An unnecessary type or const parameter was given in a type alias.
- [ ] [`E0092`](https://doc.rust-lang.org/error_codes/E0092.html)
  - **Error Description:** An undefined atomic operation function was declared.
- [x] [`E0093`](https://doc.rust-lang.org/error_codes/E0093.html)
  - **Error Description:** An unknown intrinsic function was declared.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2407
- [ ] [`E0094`](https://doc.rust-lang.org/error_codes/E0094.html)
  - **Error Description:** An invalid number of generic parameters was passed to an intrinsic function.
- [ ] [`E0106`](https://doc.rust-lang.org/error_codes/E0106.html)
  - **Error Description:** This error indicates that a lifetime is missing from a type. If it is an error
inside a function signature, the problem may be with failing to adhere to the
lifetime elision rules (see below).
- [x] [`E0107`](https://doc.rust-lang.org/error_codes/E0107.html)
  - **Error Description:** An incorrect number of generic arguments was provided.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2539
- [ ] [`E0109`](https://doc.rust-lang.org/error_codes/E0109.html)
  - **Error Description:** You tried to provide a generic argument to a type which doesn't need it.
- [ ] [`E0116`](https://doc.rust-lang.org/error_codes/E0116.html)
  - **Error Description:** An inherent implementation was defined for a type outside the current crate.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2423
- [ ] [`E0117`](https://doc.rust-lang.org/error_codes/E0117.html)
  - **Error Description:** Only traits defined in the current crate can be implemented for arbitrary types.
- [ ] [`E0118`](https://doc.rust-lang.org/error_codes/E0118.html)
  - **Error Description:** An inherent implementation was defined for something which isn't a struct,
enum, union, or trait object.
- [ ] [`E0119`](https://doc.rust-lang.org/error_codes/E0119.html)
  - **Error Description:** There are conflicting trait implementations for the same type.
- [ ] [`E0120`](https://doc.rust-lang.org/error_codes/E0120.html)
  - **Error Description:** Drop was implemented on a trait, which is not allowed: only structs and
enums can implement Drop.
- [ ] [`E0121`](https://doc.rust-lang.org/error_codes/E0121.html)
  - **Error Description:** The type placeholder `_` was used within a type on an item's signature.
- [x] [`E0124`](https://doc.rust-lang.org/error_codes/E0124.html)
  - **Error Description:** A struct was declared with two fields having the same name.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2397
- [ ] [`E0128`](https://doc.rust-lang.org/error_codes/E0128.html)
  - **Error Description:** A type parameter with default value is using forward declared identifier.
- [ ] [`E0130`](https://doc.rust-lang.org/error_codes/E0130.html)
  - **Error Description:** A pattern was declared as an argument in a foreign function declaration.
- [ ] [`E0131`](https://doc.rust-lang.org/error_codes/E0131.html)
  - **Error Description:** The `main` function was defined with generic parameters.
- [ ] [`E0132`](https://doc.rust-lang.org/error_codes/E0132.html)
  - **Error Description:** A function with the `start` attribute was declared with type parameters.
- [x] [`E0133`](https://doc.rust-lang.org/error_codes/E0133.html)
  - **Error Description:** Unsafe code was used outside of an unsafe block.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2424
- [ ] [`E0138`](https://doc.rust-lang.org/error_codes/E0138.html)
  - **Error Description:** More than one function was declared with the `#[start]` attribute.
- [ ] [`E0152`](https://doc.rust-lang.org/error_codes/E0152.html)
  - **Error Description:** A lang item was redefined.
- [ ] [`E0158`](https://doc.rust-lang.org/error_codes/E0158.html)
  - **Error Description:** An associated `const`, `const` parameter or `static` has been referenced
in a pattern.
- [ ] [`E0161`](https://doc.rust-lang.org/error_codes/E0161.html)
  - **Error Description:** A value was moved whose size was not known at compile time.
- [x] [`E0164`](https://doc.rust-lang.org/error_codes/E0164.html)
  - **Error Description:** Something which is neither a tuple struct nor a tuple variant was used as a
pattern.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2430
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2565 
- [ ] [`E0170`](https://doc.rust-lang.org/error_codes/E0170.html)
  - **Error Description:** A pattern binding is using the same name as one of the variants of a type.
- [ ] [`E0178`](https://doc.rust-lang.org/error_codes/E0178.html)
  - **Error Description:** The `+` type operator was used in an ambiguous context.
- [ ] [`E0183`](https://doc.rust-lang.org/error_codes/E0183.html)
  - **Error Description:** Manual implementation of a `Fn*` trait.
- [ ] [`E0184`](https://doc.rust-lang.org/error_codes/E0184.html)
  - **Error Description:** The `Copy` trait was implemented on a type with a `Drop` implementation.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2510
- [ ] [`E0185`](https://doc.rust-lang.org/error_codes/E0185.html)
  - **Error Description:** An associated function for a trait was defined to be static, but an
implementation of the trait declared the same function to be a method (i.e., to
take a `self` parameter).
- [ ] [`E0186`](https://doc.rust-lang.org/error_codes/E0186.html)
  - **Error Description:** An associated function for a trait was defined to be a method (i.e., to take a
`self` parameter), but an implementation of the trait declared the same function
to be static.
- [ ] [`E0191`](https://doc.rust-lang.org/error_codes/E0191.html)
  - **Error Description:** An associated type wasn't specified for a trait object.
- [ ] [`E0195`](https://doc.rust-lang.org/error_codes/E0195.html)
  - **Error Description:** The lifetime parameters of the method do not match the trait declaration.
- [ ] [`E0197`](https://doc.rust-lang.org/error_codes/E0197.html)
  - **Error Description:** An inherent implementation was marked unsafe.
- [ ] [`E0198`](https://doc.rust-lang.org/error_codes/E0198.html)
  - **Error Description:** A negative implementation was marked as unsafe.
- [ ] [`E0199`](https://doc.rust-lang.org/error_codes/E0199.html)
  - **Error Description:** A trait implementation was marked as unsafe while the trait is safe.
- [ ] [`E0200`](https://doc.rust-lang.org/error_codes/E0200.html)
  - **Error Description:** An unsafe trait was implemented without an unsafe implementation.
- [ ] [`E0201`](https://doc.rust-lang.org/error_codes/E0201.html)
  - **Error Description:** Two associated items (like methods, associated types, associated functions,
etc.) were defined with the same identifier.
- [ ] [`E0203`](https://doc.rust-lang.org/error_codes/E0203.html)
  - **Error Description:** Having multiple relaxed default bounds is unsupported.
- [ ] [`E0204`](https://doc.rust-lang.org/error_codes/E0204.html)
  - **Error Description:** The `Copy` trait was implemented on a type which contains a field that doesn't
implement the `Copy` trait.
- [ ] [`E0206`](https://doc.rust-lang.org/error_codes/E0206.html)
  - **Error Description:** The `Copy` trait was implemented on a type which is neither a struct, an
enum, nor a union.
- [ ] [`E0207`](https://doc.rust-lang.org/error_codes/E0207.html)
  - **Error Description:** A type, const or lifetime parameter that is specified for `impl` is not
constrained.
- [ ] [`E0210`](https://doc.rust-lang.org/error_codes/E0210.html)
  - **Error Description:** This error indicates a violation of one of Rust's orphan rules for trait
implementations. The rule concerns the use of type parameters in an
implementation of a foreign trait (a trait defined in another crate), and
states that type parameters must be "covered" by a local type.
- [ ] [`E0212`](https://doc.rust-lang.org/error_codes/E0212.html)
  - **Error Description:** Cannot use the associated type of
a trait with uninferred generic parameters.
- [ ] [`E0214`](https://doc.rust-lang.org/error_codes/E0214.html)
  - **Error Description:** A generic type was described using parentheses rather than angle brackets.
- [ ] [`E0220`](https://doc.rust-lang.org/error_codes/E0220.html)
  - **Error Description:** The associated type used was not defined in the trait.
- [ ] [`E0221`](https://doc.rust-lang.org/error_codes/E0221.html)
  - **Error Description:** An attempt was made to retrieve an associated type, but the type was ambiguous.
- [ ] [`E0222`](https://doc.rust-lang.org/error_codes/E0222.html)
  - **Error Description:** An attempt was made to constrain an associated type.
- [ ] [`E0223`](https://doc.rust-lang.org/error_codes/E0223.html)
  - **Error Description:** An attempt was made to retrieve an associated type, but the type was ambiguous.
- [ ] [`E0224`](https://doc.rust-lang.org/error_codes/E0224.html)
  - **Error Description:** A trait object was declared with no traits.
- [ ] [`E0225`](https://doc.rust-lang.org/error_codes/E0225.html)
  - **Error Description:** Multiple types were used as bounds for a closure or trait object.
- [ ] [`E0226`](https://doc.rust-lang.org/error_codes/E0226.html)
  - **Error Description:** More than one explicit lifetime bound was used on a trait object.
- [ ] [`E0227`](https://doc.rust-lang.org/error_codes/E0227.html)
  - **Error Description:** This error indicates that the compiler is unable to determine whether there is
exactly one unique region in the set of derived region bounds.
- [ ] [`E0228`](https://doc.rust-lang.org/error_codes/E0228.html)
  - **Error Description:** The lifetime bound for this object type cannot be deduced from context and must
be specified.
- [x] [`E0229`](https://doc.rust-lang.org/error_codes/E0229.html)
  - **Error Description:** An associated type binding was done outside of the type parameter declaration
and `where` clause.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2367
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2369
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2368
- [ ] [`E0230`](https://doc.rust-lang.org/error_codes/E0230.html)
  - **Error Description:** The `#[rustc_on_unimplemented]` attribute lets you specify a custom error
message for when a particular trait isn't implemented on a type placed in a
position that needs that trait. For example, when the following code is
compiled:
- [ ] [`E0231`](https://doc.rust-lang.org/error_codes/E0231.html)
  - **Error Description:** The `#[rustc_on_unimplemented]` attribute lets you specify a custom error
message for when a particular trait isn't implemented on a type placed in a
position that needs that trait. For example, when the following code is
compiled:
- [ ] [`E0232`](https://doc.rust-lang.org/error_codes/E0232.html)
  - **Error Description:** The `#[rustc_on_unimplemented]` attribute lets you specify a custom error
message for when a particular trait isn't implemented on a type placed in a
position that needs that trait. For example, when the following code is
compiled:
- [ ] [`E0252`](https://doc.rust-lang.org/error_codes/E0252.html)
  - **Error Description:** Two items of the same name cannot be imported without rebinding one of the
items under a new local name.
- [ ] [`E0253`](https://doc.rust-lang.org/error_codes/E0253.html)
  - **Error Description:** Attempt was made to import an unimportable value. This can happen when trying
to import a method from a trait.
- [ ] [`E0254`](https://doc.rust-lang.org/error_codes/E0254.html)
  - **Error Description:** Attempt was made to import an item whereas an extern crate with this name has
already been imported.
- [ ] [`E0255`](https://doc.rust-lang.org/error_codes/E0255.html)
  - **Error Description:** You can't import a value whose name is the same as another value defined in the
module.
- [ ] [`E0259`](https://doc.rust-lang.org/error_codes/E0259.html)
  - **Error Description:** The name chosen for an external crate conflicts with another external crate
that has been imported into the current module.
- [ ] [`E0260`](https://doc.rust-lang.org/error_codes/E0260.html)
  - **Error Description:** The name for an item declaration conflicts with an external crate's name.
- [ ] [`E0261`](https://doc.rust-lang.org/error_codes/E0261.html)
  - **Error Description:** An undeclared lifetime was used.
- [ ] [`E0262`](https://doc.rust-lang.org/error_codes/E0262.html)
  - **Error Description:** An invalid name was used for a lifetime parameter.
- [ ] [`E0264`](https://doc.rust-lang.org/error_codes/E0264.html)
  - **Error Description:** An unknown external lang item was used.
- [ ] [`E0267`](https://doc.rust-lang.org/error_codes/E0267.html)
  - **Error Description:** A loop keyword (`break` or `continue`) was used inside a closure but outside of
any loop.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2454
- [x] [`E0268`](https://doc.rust-lang.org/error_codes/E0268.html)
  - **Error Description:** A loop keyword (`break` or `continue`) was used outside of a loop.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2453
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2454
- [x] [`E0271`](https://doc.rust-lang.org/error_codes/E0271.html)
  - **Error Description:** A type mismatched an associated type of a trait.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2562
- [ ] [`E0275`](https://doc.rust-lang.org/error_codes/E0275.html)
  - **Error Description:** An evaluation of a trait requirement overflowed.
- [ ] [`E0276`](https://doc.rust-lang.org/error_codes/E0276.html)
  - **Error Description:** A trait implementation has stricter requirements than the trait definition.
- [x] [`E0277`](https://doc.rust-lang.org/error_codes/E0277.html)
  - **Error Description:** You tried to use a type which doesn't implement some trait in a place which
expected that trait.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2315
- [x] [`E0282`](https://doc.rust-lang.org/error_codes/E0282.html)
  - **Error Description:** The compiler could not infer a type and asked for a type annotation.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2524
- [ ] [`E0283`](https://doc.rust-lang.org/error_codes/E0283.html)
  - **Error Description:** An implementation cannot be chosen unambiguously because of lack of information.
- [ ] [`E0284`](https://doc.rust-lang.org/error_codes/E0284.html)
  - **Error Description:** This error occurs when the compiler is unable to unambiguously infer the
return type of a function or method which is generic on return type, such
as the `collect` method for `Iterator`s.
- [ ] [`E0307`](https://doc.rust-lang.org/error_codes/E0307.html)
  - **Error Description:** The `self` parameter in a method has an invalid "receiver type".
- [x] [`E0308`](https://doc.rust-lang.org/error_codes/E0308.html)
  - **Error Description:** Expected type did not match the received type.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2494
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2495
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2525
- [ ] [`E0309`](https://doc.rust-lang.org/error_codes/E0309.html)
  - **Error Description:** A parameter type is missing an explicit lifetime bound and may not live long
enough.
- [ ] [`E0310`](https://doc.rust-lang.org/error_codes/E0310.html)
  - **Error Description:** A parameter type is missing a lifetime constraint or has a lifetime that
does not live long enough.
- [ ] [`E0311`](https://doc.rust-lang.org/error_codes/E0311.html)
  - **Error Description:** This error occurs when there is an unsatisfied outlives bound involving an
elided region and a generic type parameter or associated type.
- [ ] [`E0316`](https://doc.rust-lang.org/error_codes/E0316.html)
  - **Error Description:** A `where` clause contains a nested quantification over lifetimes.
- [ ] [`E0317`](https://doc.rust-lang.org/error_codes/E0317.html)
  - **Error Description:** An `if` expression is missing an `else` block.
- [ ] [`E0320`](https://doc.rust-lang.org/error_codes/E0320.html)
  - **Error Description:** Recursion limit reached while creating drop-check rules.
- [ ] [`E0321`](https://doc.rust-lang.org/error_codes/E0321.html)
  - **Error Description:** A cross-crate opt-out trait was implemented on something which wasn't a struct
or enum type.
- [ ] [`E0322`](https://doc.rust-lang.org/error_codes/E0322.html)
  - **Error Description:** A built-in trait was implemented explicitly. All implementations of the trait
are provided automatically by the compiler.
- [x] [`E0323`](https://doc.rust-lang.org/error_codes/E0323.html)
  - **Error Description:** An associated const was implemented when another trait item was expected.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2445
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2481
- [ ] [`E0324`](https://doc.rust-lang.org/error_codes/E0324.html)
  - **Error Description:** A method was implemented when another trait item was expected.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2478
- [ ] [`E0325`](https://doc.rust-lang.org/error_codes/E0325.html)
  - **Error Description:** An associated type was implemented when another trait item was expected.
- [ ] [`E0326`](https://doc.rust-lang.org/error_codes/E0326.html)
  - **Error Description:** An implementation of a trait doesn't match the type constraint.
- [ ] [`E0328`](https://doc.rust-lang.org/error_codes/E0328.html)
  - **Error Description:** The Unsize trait should not be implemented directly. All implementations of
Unsize are provided automatically by the compiler.
- [ ] [`E0364`](https://doc.rust-lang.org/error_codes/E0364.html)
  - **Error Description:** Private items cannot be publicly re-exported. This error indicates that you
attempted to `pub use` a type or value that was not itself public.
- [ ] [`E0365`](https://doc.rust-lang.org/error_codes/E0365.html)
  - **Error Description:** Private modules cannot be publicly re-exported. This error indicates that you
attempted to `pub use` a module that was not itself public.
- [ ] [`E0366`](https://doc.rust-lang.org/error_codes/E0366.html)
  - **Error Description:** An attempt was made to implement `Drop` on a concrete specialization of a
generic type. An example is shown below:
- [ ] [`E0367`](https://doc.rust-lang.org/error_codes/E0367.html)
  - **Error Description:** An attempt was made to implement `Drop` on a specialization of a generic type.
- [ ] [`E0368`](https://doc.rust-lang.org/error_codes/E0368.html)
  - **Error Description:** A binary assignment operator like `+=` or `^=` was applied to a type that
doesn't support it.
- [ ] [`E0369`](https://doc.rust-lang.org/error_codes/E0369.html)
  - **Error Description:** A binary operation was attempted on a type which doesn't support it.
- [ ] [`E0370`](https://doc.rust-lang.org/error_codes/E0370.html)
  - **Error Description:** The maximum value of an enum was reached, so it cannot be automatically
set in the next enum value.
- [ ] [`E0371`](https://doc.rust-lang.org/error_codes/E0371.html)
  - **Error Description:** A trait was implemented on another which already automatically implemented it.
- [ ] [`E0373`](https://doc.rust-lang.org/error_codes/E0373.html)
  - **Error Description:** A captured variable in a closure may not live long enough.
- [ ] [`E0374`](https://doc.rust-lang.org/error_codes/E0374.html)
  - **Error Description:** `CoerceUnsized` was implemented on a struct which does not contain a field with
an unsized type.
- [ ] [`E0375`](https://doc.rust-lang.org/error_codes/E0375.html)
  - **Error Description:** `CoerceUnsized` was implemented on a struct which contains more than one field
with an unsized type.
- [ ] [`E0376`](https://doc.rust-lang.org/error_codes/E0376.html)
  - **Error Description:** `CoerceUnsized` was implemented on something that isn't a struct.
- [ ] [`E0377`](https://doc.rust-lang.org/error_codes/E0377.html)
  - **Error Description:** The trait `CoerceUnsized` may only be implemented for a coercion between
structures with the same definition.
- [ ] [`E0378`](https://doc.rust-lang.org/error_codes/E0378.html)
  - **Error Description:** The `DispatchFromDyn` trait was implemented on something which is not a pointer
or a newtype wrapper around a pointer.
- [ ] [`E0379`](https://doc.rust-lang.org/error_codes/E0379.html)
  - **Error Description:** A trait method was declared const.
- [x] [`E0380`](https://doc.rust-lang.org/error_codes/E0380.html)
  - **Error Description:** An auto trait was declared with a method or an associated item.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2527
- [ ] [`E0381`](https://doc.rust-lang.org/error_codes/E0381.html)
  - **Error Description:** It is not allowed to use or capture an uninitialized variable.
- [ ] [`E0382`](https://doc.rust-lang.org/error_codes/E0382.html)
  - **Error Description:** A variable was used after its contents have been moved elsewhere.
- [ ] [`E0384`](https://doc.rust-lang.org/error_codes/E0384.html)
  - **Error Description:** An immutable variable was reassigned.
- [ ] [`E0390`](https://doc.rust-lang.org/error_codes/E0390.html)
  - **Error Description:** A method or constant was implemented on a primitive type.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2500
- [x] [`E0391`](https://doc.rust-lang.org/error_codes/E0391.html)
  - **Error Description:** A type dependency cycle has been encountered.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2561
- [ ] [`E0392`](https://doc.rust-lang.org/error_codes/E0392.html)
  - **Error Description:** A type or lifetime parameter has been declared but is not actually used.
- [ ] [`E0393`](https://doc.rust-lang.org/error_codes/E0393.html)
  - **Error Description:** A type parameter which references `Self` in its default value was not specified.
- [ ] [`E0399`](https://doc.rust-lang.org/error_codes/E0399.html)
  - **Error Description:** #### Note: this error code is no longer emitted by the compiler
- [ ] [`E0401`](https://doc.rust-lang.org/error_codes/E0401.html)
  - **Error Description:** Inner items do not inherit type or const parameters from the functions
they are embedded in.
- [ ] [`E0403`](https://doc.rust-lang.org/error_codes/E0403.html)
  - **Error Description:** Some type parameters have the same name.
- [ ] [`E0404`](https://doc.rust-lang.org/error_codes/E0404.html)
  - **Error Description:** A type that is not a trait was used in a trait position, such as a bound
or `impl`.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2499
- [ ] [`E0405`](https://doc.rust-lang.org/error_codes/E0405.html)
  - **Error Description:** The code refers to a trait that is not in scope.
- [ ] [`E0407`](https://doc.rust-lang.org/error_codes/E0407.html)
  - **Error Description:** A definition of a method not in the implemented trait was given in a trait
implementation.
- [ ] [`E0408`](https://doc.rust-lang.org/error_codes/E0408.html)
  - **Error Description:** An "or" pattern was used where the variable bindings are not consistently bound
across patterns.
- [ ] [`E0409`](https://doc.rust-lang.org/error_codes/E0409.html)
  - **Error Description:** An "or" pattern was used where the variable bindings are not consistently bound
across patterns.
- [ ] [`E0411`](https://doc.rust-lang.org/error_codes/E0411.html)
  - **Error Description:** The `Self` keyword was used outside an impl, trait, or type definition.
- [x] [`E0412`](https://doc.rust-lang.org/error_codes/E0412.html)
  - **Error Description:** A used type name is not in scope.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2534
- [ ] [`E0415`](https://doc.rust-lang.org/error_codes/E0415.html)
  - **Error Description:** More than one function parameter have the same name.
- [ ] [`E0416`](https://doc.rust-lang.org/error_codes/E0416.html)
  - **Error Description:** An identifier is bound more than once in a pattern.
- [ ] [`E0422`](https://doc.rust-lang.org/error_codes/E0422.html)
  - **Error Description:** An identifier that is neither defined nor a struct was used.
- [x] [`E0423`](https://doc.rust-lang.org/error_codes/E0423.html)
  - **Error Description:** An identifier was used like a function name or a value was expected and the
identifier exists but it belongs to a different namespace.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2433
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2434
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2432
- [ ] [`E0424`](https://doc.rust-lang.org/error_codes/E0424.html)
  - **Error Description:** The `self` keyword was used inside of an associated function without a "`self`
receiver" parameter.
- [x] [`E0425`](https://doc.rust-lang.org/error_codes/E0425.html)
  - **Error Description:** An unresolved name was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2383
- [x] [`E0426`](https://doc.rust-lang.org/error_codes/E0426.html)
  - **Error Description:** An undeclared label was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2502
- [ ] [`E0428`](https://doc.rust-lang.org/error_codes/E0428.html)
  - **Error Description:** A type or module has been defined more than once.
- [ ] [`E0429`](https://doc.rust-lang.org/error_codes/E0429.html)
  - **Error Description:** The `self` keyword cannot appear alone as the last segment in a `use`
declaration.
- [ ] [`E0430`](https://doc.rust-lang.org/error_codes/E0430.html)
  - **Error Description:** The `self` import appears more than once in the list.
- [ ] [`E0431`](https://doc.rust-lang.org/error_codes/E0431.html)
  - **Error Description:** An invalid `self` import was made.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2501
- [ ] [`E0432`](https://doc.rust-lang.org/error_codes/E0432.html)
  - **Error Description:** An import was unresolved.
- [x] [`E0433`](https://doc.rust-lang.org/error_codes/E0433.html)
  - **Error Description:** An undeclared crate, module, or type was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2301
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2508
  - wrong error on: <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2511
- [ ] [`E0434`](https://doc.rust-lang.org/error_codes/E0434.html)
  - **Error Description:** A variable used inside an inner function comes from a dynamic environment.
- [ ] [`E0435`](https://doc.rust-lang.org/error_codes/E0435.html)
  - **Error Description:** A non-constant value was used in a constant expression.
- [ ] [`E0436`](https://doc.rust-lang.org/error_codes/E0436.html)
  - **Error Description:** The functional record update syntax was used on something other than a struct.
- [ ] [`E0437`](https://doc.rust-lang.org/error_codes/E0437.html)
  - **Error Description:** An associated type whose name does not match any of the associated types
in the trait was used when implementing the trait.
- [ ] [`E0438`](https://doc.rust-lang.org/error_codes/E0438.html)
  - **Error Description:** An associated constant whose name does not match any of the associated constants
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2481
in the trait was used when implementing the trait.
- [ ] [`E0445`](https://doc.rust-lang.org/error_codes/E0445.html)
  - **Error Description:** A private trait was used on a public type parameter bound.
- [ ] [`E0446`](https://doc.rust-lang.org/error_codes/E0446.html)
  - **Error Description:** A private type was used in a public type signature.
- [ ] [`E0449`](https://doc.rust-lang.org/error_codes/E0449.html)
  - **Error Description:** A visibility qualifier was used where one is not permitted. Visibility
qualifiers are not permitted on enum variants, trait items, impl blocks, and
extern blocks, as they already share the visibility of the parent item.
- [ ] [`E0451`](https://doc.rust-lang.org/error_codes/E0451.html)
  - **Error Description:** A struct constructor with private fields was invoked.
- [ ] [`E0452`](https://doc.rust-lang.org/error_codes/E0452.html)
  - **Error Description:** An invalid lint attribute has been given.
- [ ] [`E0453`](https://doc.rust-lang.org/error_codes/E0453.html)
  - **Error Description:** A lint check attribute was overruled by a `forbid` directive set as an
attribute on an enclosing scope, or on the command line with the `-F` option.
- [ ] [`E0454`](https://doc.rust-lang.org/error_codes/E0454.html)
  - **Error Description:** A link name was given with an empty name.
- [ ] [`E0455`](https://doc.rust-lang.org/error_codes/E0455.html)
  - **Error Description:** Some linking kinds are target-specific and not supported on all platforms.
- [ ] [`E0457`](https://doc.rust-lang.org/error_codes/E0457.html)
  - **Error Description:** Plugin `..` only found in rlib format, but must be available in dylib format.
- [ ] [`E0458`](https://doc.rust-lang.org/error_codes/E0458.html)
  - **Error Description:** An unknown "kind" was specified for a link attribute.
- [ ] [`E0459`](https://doc.rust-lang.org/error_codes/E0459.html)
  - **Error Description:** A link was used without a name parameter.
- [ ] [`E0460`](https://doc.rust-lang.org/error_codes/E0460.html)
  - **Error Description:** Found possibly newer version of crate `..` which `..` depends on.
- [ ] [`E0461`](https://doc.rust-lang.org/error_codes/E0461.html)
  - **Error Description:** Couldn't find crate `..` with expected target triple `..`.
- [ ] [`E0462`](https://doc.rust-lang.org/error_codes/E0462.html)
  - **Error Description:** Found `staticlib` `..` instead of `rlib` or `dylib`.
- [ ] [`E0463`](https://doc.rust-lang.org/error_codes/E0463.html)
  - **Error Description:** A plugin/crate was declared but cannot be found.
- [ ] [`E0464`](https://doc.rust-lang.org/error_codes/E0464.html)
  - **Error Description:** The compiler found multiple library files with the requested crate name.
- [ ] [`E0466`](https://doc.rust-lang.org/error_codes/E0466.html)
  - **Error Description:** Macro import declaration was malformed.
- [ ] [`E0468`](https://doc.rust-lang.org/error_codes/E0468.html)
  - **Error Description:** A non-root module tried to import macros from another crate.
- [ ] [`E0469`](https://doc.rust-lang.org/error_codes/E0469.html)
  - **Error Description:** A macro listed for import was not found.
- [ ] [`E0472`](https://doc.rust-lang.org/error_codes/E0472.html)
  - **Error Description:** Inline assembly (`asm!`) is not supported on this target.
- [ ] [`E0476`](https://doc.rust-lang.org/error_codes/E0476.html)
  - **Error Description:** The coerced type does not outlive the value being coerced to.
- [ ] [`E0478`](https://doc.rust-lang.org/error_codes/E0478.html)
  - **Error Description:** A lifetime bound was not satisfied.
- [ ] [`E0491`](https://doc.rust-lang.org/error_codes/E0491.html)
  - **Error Description:** A reference has a longer lifetime than the data it references.
- [ ] [`E0492`](https://doc.rust-lang.org/error_codes/E0492.html)
  - **Error Description:** A borrow of a constant containing interior mutability was attempted.
- [ ] [`E0493`](https://doc.rust-lang.org/error_codes/E0493.html)
  - **Error Description:** A value with a custom `Drop` implementation may be dropped during const-eval.
- [ ] [`E0496`](https://doc.rust-lang.org/error_codes/E0496.html)
  - **Error Description:** A lifetime name is shadowing another lifetime name.
- [ ] [`E0498`](https://doc.rust-lang.org/error_codes/E0498.html)
  - **Error Description:** The `plugin` attribute was malformed.
- [ ] [`E0499`](https://doc.rust-lang.org/error_codes/E0499.html)
  - **Error Description:** A variable was borrowed as mutable more than once.
- [ ] [`E0500`](https://doc.rust-lang.org/error_codes/E0500.html)
  - **Error Description:** A borrowed variable was used by a closure.
- [ ] [`E0501`](https://doc.rust-lang.org/error_codes/E0501.html)
  - **Error Description:** A mutable variable is used but it is already captured by a closure.
- [ ] [`E0502`](https://doc.rust-lang.org/error_codes/E0502.html)
  - **Error Description:** A variable already borrowed as immutable was borrowed as mutable.
- [ ] [`E0503`](https://doc.rust-lang.org/error_codes/E0503.html)
  - **Error Description:** A value was used after it was mutably borrowed.
- [ ] [`E0505`](https://doc.rust-lang.org/error_codes/E0505.html)
  - **Error Description:** A value was moved out while it was still borrowed.
- [ ] [`E0506`](https://doc.rust-lang.org/error_codes/E0506.html)
  - **Error Description:** An attempt was made to assign to a borrowed value.
- [ ] [`E0507`](https://doc.rust-lang.org/error_codes/E0507.html)
  - **Error Description:** A borrowed value was moved out.
- [ ] [`E0508`](https://doc.rust-lang.org/error_codes/E0508.html)
  - **Error Description:** A value was moved out of a non-copy fixed-size array.
- [ ] [`E0509`](https://doc.rust-lang.org/error_codes/E0509.html)
  - **Error Description:** This error occurs when an attempt is made to move out of a value whose type
implements the `Drop` trait.
- [ ] [`E0510`](https://doc.rust-lang.org/error_codes/E0510.html)
  - **Error Description:** The matched value was assigned in a match guard.
- [ ] [`E0511`](https://doc.rust-lang.org/error_codes/E0511.html)
  - **Error Description:** Invalid monomorphization of an intrinsic function was used.
- [ ] [`E0512`](https://doc.rust-lang.org/error_codes/E0512.html)
  - **Error Description:** Transmute with two differently sized types was attempted.
- [ ] [`E0514`](https://doc.rust-lang.org/error_codes/E0514.html)
  - **Error Description:** Dependency compiled with different version of `rustc`.
- [ ] [`E0515`](https://doc.rust-lang.org/error_codes/E0515.html)
  - **Error Description:** A reference to a local variable was returned.
- [ ] [`E0516`](https://doc.rust-lang.org/error_codes/E0516.html)
  - **Error Description:** The `typeof` keyword is currently reserved but unimplemented.
- [ ] [`E0517`](https://doc.rust-lang.org/error_codes/E0517.html)
  - **Error Description:** A `#[repr(..)]` attribute was placed on an unsupported item.
- [ ] [`E0518`](https://doc.rust-lang.org/error_codes/E0518.html)
  - **Error Description:** An `#[inline(..)]` attribute was incorrectly placed on something other than a
function or method.
- [ ] [`E0519`](https://doc.rust-lang.org/error_codes/E0519.html)
  - **Error Description:** The current crate is indistinguishable from one of its dependencies, in terms
of metadata.
- [ ] [`E0520`](https://doc.rust-lang.org/error_codes/E0520.html)
  - **Error Description:** A non-default implementation was already made on this type so it cannot be
specialized further.
- [ ] [`E0521`](https://doc.rust-lang.org/error_codes/E0521.html)
  - **Error Description:** Borrowed data escapes outside of closure.
- [ ] [`E0522`](https://doc.rust-lang.org/error_codes/E0522.html)
  - **Error Description:** The lang attribute was used in an invalid context.
- [ ] [`E0524`](https://doc.rust-lang.org/error_codes/E0524.html)
  - **Error Description:** A variable which requires unique access is being used in more than one closure
at the same time.
- [ ] [`E0525`](https://doc.rust-lang.org/error_codes/E0525.html)
  - **Error Description:** A closure was used but didn't implement the expected trait.
- [ ] [`E0527`](https://doc.rust-lang.org/error_codes/E0527.html)
  - **Error Description:** The number of elements in an array or slice pattern differed from the number of
elements in the array being matched.
- [ ] [`E0528`](https://doc.rust-lang.org/error_codes/E0528.html)
  - **Error Description:** An array or slice pattern required more elements than were present in the
matched array.
- [ ] [`E0529`](https://doc.rust-lang.org/error_codes/E0529.html)
  - **Error Description:** An array or slice pattern was matched against some other type.
- [ ] [`E0530`](https://doc.rust-lang.org/error_codes/E0530.html)
  - **Error Description:** A binding shadowed something it shouldn't.
- [ ] [`E0531`](https://doc.rust-lang.org/error_codes/E0531.html)
  - **Error Description:** An unknown tuple struct/variant has been used.
- [x] [`E0532`](https://doc.rust-lang.org/error_codes/E0532.html)
  - **Error Description:** Pattern arm did not match expected kind.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2563
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2324
- [ ] [`E0533`](https://doc.rust-lang.org/error_codes/E0533.html)
  - **Error Description:** An item which isn't a unit struct, a variant, nor a constant has been used as a
match pattern.
- [ ] [`E0534`](https://doc.rust-lang.org/error_codes/E0534.html)
  - **Error Description:** The `inline` attribute was malformed.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2558
- [ ] [`E0535`](https://doc.rust-lang.org/error_codes/E0535.html)
  - **Error Description:** An unknown argument was given to the `inline` attribute.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2559
- [ ] [`E0536`](https://doc.rust-lang.org/error_codes/E0536.html)
  - **Error Description:** The `not` cfg-predicate was malformed.
- [ ] [`E0537`](https://doc.rust-lang.org/error_codes/E0537.html)
  - **Error Description:** An unknown predicate was used inside the `cfg` attribute.
- [ ] [`E0538`](https://doc.rust-lang.org/error_codes/E0538.html)
  - **Error Description:** Attribute contains same meta item more than once.
- [ ] [`E0539`](https://doc.rust-lang.org/error_codes/E0539.html)
  - **Error Description:** An invalid meta-item was used inside an attribute.
- [x] [`E0541`](https://doc.rust-lang.org/error_codes/E0541.html)
  - **Error Description:** An unknown meta item was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2526
- [ ] [`E0542`](https://doc.rust-lang.org/error_codes/E0542.html)
  - **Error Description:** The `since` value is missing in a stability attribute.
- [ ] [`E0543`](https://doc.rust-lang.org/error_codes/E0543.html)
  - **Error Description:** The `note` value is missing in a stability attribute.
- [ ] [`E0544`](https://doc.rust-lang.org/error_codes/E0544.html)
  - **Error Description:** Multiple stability attributes were declared on the same item.
- [ ] [`E0545`](https://doc.rust-lang.org/error_codes/E0545.html)
  - **Error Description:** The `issue` value is incorrect in a stability attribute.
- [ ] [`E0546`](https://doc.rust-lang.org/error_codes/E0546.html)
  - **Error Description:** The `feature` value is missing in a stability attribute.
- [ ] [`E0547`](https://doc.rust-lang.org/error_codes/E0547.html)
  - **Error Description:** The `issue` value is missing in a stability attribute.
- [ ] [`E0549`](https://doc.rust-lang.org/error_codes/E0549.html)
  - **Error Description:** A `deprecated` attribute wasn't paired with a `stable`/`unstable` attribute with
`#![feature(staged_api)]` enabled.
- [ ] [`E0550`](https://doc.rust-lang.org/error_codes/E0550.html)
  - **Error Description:** #### Note: this error code is no longer emitted by the compiler
- [ ] [`E0551`](https://doc.rust-lang.org/error_codes/E0551.html)
  - **Error Description:** An invalid meta-item was used inside an attribute.
- [ ] [`E0552`](https://doc.rust-lang.org/error_codes/E0552.html)
  - **Error Description:** A unrecognized representation attribute was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2517
  - These are some reference links: 
    * https://doc.rust-lang.org/error_codes/E0658.html
    * https://doc.rust-lang.org/error_codes/E0552.html
    * <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/915
    * <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/1188
    * https://doc.rust-lang.org/reference/type-layout.html#representations
    * https://github.com/rust-lang/rust/pull/110083
    * https://github.com/rust-lang/rust/pull/103693
    * https://godbolt.org/z/5cj81hKa3
    * https://godbolt.org/z/7Y4K831Kv
    * https://github.com/rust-lang/rust/issues/56071
- [ ] [`E0554`](https://doc.rust-lang.org/error_codes/E0554.html)
  - **Error Description:** Feature attributes are only allowed on the nightly release channel. Stable or
beta compilers will not comply.
- [ ] [`E0556`](https://doc.rust-lang.org/error_codes/E0556.html)
  - **Error Description:** The `feature` attribute was badly formed.
- [ ] [`E0557`](https://doc.rust-lang.org/error_codes/E0557.html)
  - **Error Description:** A feature attribute named a feature that has been removed.
- [ ] [`E0559`](https://doc.rust-lang.org/error_codes/E0559.html)
  - **Error Description:** An unknown field was specified into an enum's structure variant.
- [ ] [`E0560`](https://doc.rust-lang.org/error_codes/E0560.html)
  - **Error Description:** An unknown field was specified into a structure.
- [ ] [`E0561`](https://doc.rust-lang.org/error_codes/E0561.html)
  - **Error Description:** A non-ident or non-wildcard pattern has been used as a parameter of a function
pointer type.
- [ ] [`E0562`](https://doc.rust-lang.org/error_codes/E0562.html)
  - **Error Description:** Abstract return types (written `impl Trait` for some trait `Trait`) are only
allowed as function and inherent impl return types.
- [ ] [`E0565`](https://doc.rust-lang.org/error_codes/E0565.html)
  - **Error Description:** A literal was used in a built-in attribute that doesn't support literals.
- [ ] [`E0566`](https://doc.rust-lang.org/error_codes/E0566.html)
  - **Error Description:** Conflicting representation hints have been used on a same item.
- [ ] [`E0567`](https://doc.rust-lang.org/error_codes/E0567.html)
  - **Error Description:** Generics have been used on an auto trait.
- [ ] [`E0568`](https://doc.rust-lang.org/error_codes/E0568.html)
  - **Error Description:** A super trait has been added to an auto trait.
- [ ] [`E0569`](https://doc.rust-lang.org/error_codes/E0569.html)
  - **Error Description:** If an impl has a generic parameter with the `#[may_dangle]` attribute, then
that impl must be declared as an `unsafe impl`.
- [ ] [`E0570`](https://doc.rust-lang.org/error_codes/E0570.html)
  - **Error Description:** The requested ABI is unsupported by the current target.
- [x] [`E0571`](https://doc.rust-lang.org/error_codes/E0571.html)
  - **Error Description:** A `break` statement with an argument appeared in a non-`loop` loop.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2455
- [x] [`E0572`](https://doc.rust-lang.org/error_codes/E0572.html)
  - **Error Description:** A return statement was found outside of a function body.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2477
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2493
- [x] [`E0573`](https://doc.rust-lang.org/error_codes/E0573.html)
  - **Error Description:** Something other than a type has been used when one was expected.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2479
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2568
- [ ] [`E0574`](https://doc.rust-lang.org/error_codes/E0574.html)
  - **Error Description:** Something other than a struct, variant or union has been used when one was
expected.
- [ ] [`E0575`](https://doc.rust-lang.org/error_codes/E0575.html)
  - **Error Description:** Something other than a type or an associated type was given.
- [ ] [`E0576`](https://doc.rust-lang.org/error_codes/E0576.html)
  - **Error Description:** An associated item wasn't found in the given type.
- [ ] [`E0577`](https://doc.rust-lang.org/error_codes/E0577.html)
  - **Error Description:** Something other than a module was found in visibility scope.
- [ ] [`E0578`](https://doc.rust-lang.org/error_codes/E0578.html)
  - **Error Description:** A module cannot be found and therefore, the visibility cannot be determined.
- [ ] [`E0579`](https://doc.rust-lang.org/error_codes/E0579.html)
  - **Error Description:** A lower range wasn't less than the upper range.
- [ ] [`E0580`](https://doc.rust-lang.org/error_codes/E0580.html)
  - **Error Description:** The `main` function was incorrectly declared.
- [ ] [`E0581`](https://doc.rust-lang.org/error_codes/E0581.html)
  - **Error Description:** In a `fn` type, a lifetime appears only in the return type
and not in the arguments types.
- [ ] [`E0582`](https://doc.rust-lang.org/error_codes/E0582.html)
  - **Error Description:** A lifetime is only present in an associated-type binding, and not in the input
types to the trait.
- [ ] [`E0583`](https://doc.rust-lang.org/error_codes/E0583.html)
  - **Error Description:** A file wasn't found for an out-of-line module.
- [ ] [`E0584`](https://doc.rust-lang.org/error_codes/E0584.html)
  - **Error Description:** A doc comment that is not attached to anything has been encountered.
- [ ] [`E0585`](https://doc.rust-lang.org/error_codes/E0585.html)
  - **Error Description:** A documentation comment that doesn't document anything was found.
- [ ] [`E0586`](https://doc.rust-lang.org/error_codes/E0586.html)
  - **Error Description:** An inclusive range was used with no end.
- [ ] [`E0587`](https://doc.rust-lang.org/error_codes/E0587.html)
  - **Error Description:** A type has both `packed` and `align` representation hints.
- [ ] [`E0588`](https://doc.rust-lang.org/error_codes/E0588.html)
  - **Error Description:** A type with `packed` representation hint has a field with `align`
representation hint.
- [ ] [`E0589`](https://doc.rust-lang.org/error_codes/E0589.html)
  - **Error Description:** The value of `N` that was specified for `repr(align(N))` was not a power
of two, or was greater than 2^29.
- [ ] [`E0590`](https://doc.rust-lang.org/error_codes/E0590.html)
  - **Error Description:** `break` or `continue` keywords were used in a condition of a `while` loop
without a label.
- [ ] [`E0591`](https://doc.rust-lang.org/error_codes/E0591.html)
  - **Error Description:** Per [RFC 401][rfc401], if you have a function declaration `foo`:
- [x] [`E0592`](https://doc.rust-lang.org/error_codes/E0592.html)
  - **Error Description:** This error occurs when you defined methods or associated functions with same
name.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2555
- [ ] [`E0593`](https://doc.rust-lang.org/error_codes/E0593.html)
  - **Error Description:** You tried to supply an `Fn`-based type with an incorrect number of arguments
than what was expected.
- [ ] [`E0594`](https://doc.rust-lang.org/error_codes/E0594.html)
  - **Error Description:** A non-mutable value was assigned a value.
- [ ] [`E0596`](https://doc.rust-lang.org/error_codes/E0596.html)
  - **Error Description:** This error occurs because you tried to mutably borrow a non-mutable variable.
- [ ] [`E0597`](https://doc.rust-lang.org/error_codes/E0597.html)
  - **Error Description:** This error occurs because a value was dropped while it was still borrowed.
- [x] [`E0599`](https://doc.rust-lang.org/error_codes/E0599.html)
  - **Error Description:** This error occurs when a method is used on a type which doesn't implement it:
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2571
- [ ] [`E0600`](https://doc.rust-lang.org/error_codes/E0600.html)
  - **Error Description:** An unary operator was used on a type which doesn't implement it.
- [ ] [`E0601`](https://doc.rust-lang.org/error_codes/E0601.html)
  - **Error Description:** No `main` function was found in a binary crate.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2512
- [ ] [`E0602`](https://doc.rust-lang.org/error_codes/E0602.html)
  - **Error Description:** An unknown or invalid lint was used on the command line.
- [x] [`E0603`](https://doc.rust-lang.org/error_codes/E0603.html)
  - **Error Description:** A private item was used outside its scope.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg> https://github.com/Rust-GCC/gccrs/pull/2597
- [x] [`E0604`](https://doc.rust-lang.org/error_codes/E0604.html)
  - **Error Description:** A cast to `char` was attempted on a type other than `u8`.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2528
- [ ] [`E0605`](https://doc.rust-lang.org/error_codes/E0605.html)
  - **Error Description:** An invalid cast was attempted.
- [x] [`E0606`](https://doc.rust-lang.org/error_codes/E0606.html)
  - **Error Description:** An incompatible cast was attempted.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2528
- [ ] [`E0607`](https://doc.rust-lang.org/error_codes/E0607.html)
  - **Error Description:** A cast between a thin and a fat pointer was attempted.
- [ ] [`E0608`](https://doc.rust-lang.org/error_codes/E0608.html)
  - **Error Description:** An attempt to use index on a type which doesn't implement the `std::ops::Index`
trait was performed.
- [ ] [`E0609`](https://doc.rust-lang.org/error_codes/E0609.html)
  - **Error Description:** Attempted to access a nonexistent field in a struct.
- [ ] [`E0610`](https://doc.rust-lang.org/error_codes/E0610.html)
  - **Error Description:** Attempted to access a field on a primitive type.
- [ ] [`E0614`](https://doc.rust-lang.org/error_codes/E0614.html)
  - **Error Description:** Attempted to dereference a variable which cannot be dereferenced.
- [ ] [`E0615`](https://doc.rust-lang.org/error_codes/E0615.html)
  - **Error Description:** Attempted to access a method like a field.
- [ ] [`E0616`](https://doc.rust-lang.org/error_codes/E0616.html)
  - **Error Description:** Attempted to access a private field on a struct.
- [ ] [`E0617`](https://doc.rust-lang.org/error_codes/E0617.html)
  - **Error Description:** Attempted to pass an invalid type of variable into a variadic function.
- [ ] [`E0618`](https://doc.rust-lang.org/error_codes/E0618.html)
  - **Error Description:** Attempted to call something which isn't a function nor a method.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2434
- [x] [`E0620`](https://doc.rust-lang.org/error_codes/E0620.html)
  - **Error Description:** A cast to an unsized type was attempted.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2528
- [ ] [`E0621`](https://doc.rust-lang.org/error_codes/E0621.html)
  - **Error Description:** This error code indicates a mismatch between the lifetimes appearing in the
function signature (i.e., the parameter types and the return type) and the
data-flow found in the function body.
- [ ] [`E0622`](https://doc.rust-lang.org/error_codes/E0622.html)
  - **Error Description:** An intrinsic was declared without being a function.
- [ ] [`E0623`](https://doc.rust-lang.org/error_codes/E0623.html)
  - **Error Description:** A lifetime didn't match what was expected.
- [ ] [`E0624`](https://doc.rust-lang.org/error_codes/E0624.html)
  - **Error Description:** A private item was used outside of its scope.
- [ ] [`E0625`](https://doc.rust-lang.org/error_codes/E0625.html)
  - **Error Description:** A compile-time const variable is referring to a thread-local static variable.
- [ ] [`E0626`](https://doc.rust-lang.org/error_codes/E0626.html)
  - **Error Description:** This error occurs because a borrow in a generator persists across a
yield point.
- [ ] [`E0627`](https://doc.rust-lang.org/error_codes/E0627.html)
  - **Error Description:** A yield expression was used outside of the generator literal.
- [ ] [`E0628`](https://doc.rust-lang.org/error_codes/E0628.html)
  - **Error Description:** More than one parameter was used for a generator.
- [ ] [`E0631`](https://doc.rust-lang.org/error_codes/E0631.html)
  - **Error Description:** This error indicates a type mismatch in closure arguments.
- [ ] [`E0634`](https://doc.rust-lang.org/error_codes/E0634.html)
  - **Error Description:** A type has conflicting `packed` representation hints.
- [x] [`E0635`](https://doc.rust-lang.org/error_codes/E0635.html)
  - **Error Description:** The `#![feature]` attribute specified an unknown feature.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2513
- [ ] [`E0636`](https://doc.rust-lang.org/error_codes/E0636.html)
  - **Error Description:** A `#![feature]` attribute was declared multiple times.
- [ ] [`E0637`](https://doc.rust-lang.org/error_codes/E0637.html)
  - **Error Description:** `'_` lifetime name or `&T` without an explicit lifetime name has been used
on illegal place.
- [ ] [`E0638`](https://doc.rust-lang.org/error_codes/E0638.html)
  - **Error Description:** This error indicates that the struct, enum or enum variant must be matched
non-exhaustively as it has been marked as `non_exhaustive`.
- [ ] [`E0639`](https://doc.rust-lang.org/error_codes/E0639.html)
  - **Error Description:** This error indicates that the struct, enum or enum variant cannot be
instantiated from outside of the defining crate as it has been marked
as `non_exhaustive` and as such more fields/variants may be added in
future that could cause adverse side effects for this code.
- [ ] [`E0640`](https://doc.rust-lang.org/error_codes/E0640.html)
  - **Error Description:** #### This error code is internal to the compiler and will not be emitted with normal Rust code.
- [ ] [`E0641`](https://doc.rust-lang.org/error_codes/E0641.html)
  - **Error Description:** Attempted to cast to/from a pointer with an unknown kind.
- [ ] [`E0642`](https://doc.rust-lang.org/error_codes/E0642.html)
  - **Error Description:** Trait methods currently cannot take patterns as arguments.
- [ ] [`E0643`](https://doc.rust-lang.org/error_codes/E0643.html)
  - **Error Description:** This error indicates that there is a mismatch between generic parameters and
impl Trait parameters in a trait declaration versus its impl.
- [ ] [`E0644`](https://doc.rust-lang.org/error_codes/E0644.html)
  - **Error Description:** A closure or generator was constructed that references its own type.
- [ ] [`E0646`](https://doc.rust-lang.org/error_codes/E0646.html)
  - **Error Description:** It is not possible to define `main` with a where clause.
- [ ] [`E0647`](https://doc.rust-lang.org/error_codes/E0647.html)
  - **Error Description:** The `start` function was defined with a where clause.
- [ ] [`E0648`](https://doc.rust-lang.org/error_codes/E0648.html)
  - **Error Description:** An `export_name` attribute contains null characters (`\0`).
- [ ] [`E0657`](https://doc.rust-lang.org/error_codes/E0657.html)
  - **Error Description:** A lifetime bound on a trait implementation was captured at an incorrect place.
- [x] [`E0658`](https://doc.rust-lang.org/error_codes/E0658.html)
  - **Error Description:** An unstable feature was used.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2536
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2408
- [ ] [`E0659`](https://doc.rust-lang.org/error_codes/E0659.html)
  - **Error Description:** An item usage is ambiguous.
- [ ] [`E0666`](https://doc.rust-lang.org/error_codes/E0666.html)
  - **Error Description:** `impl Trait` types cannot appear nested in the generic arguments of other
`impl Trait` types.
- [ ] [`E0667`](https://doc.rust-lang.org/error_codes/E0667.html)
  - **Error Description:** `impl Trait` is not allowed in path parameters.
- [ ] [`E0670`](https://doc.rust-lang.org/error_codes/E0670.html)
  - **Error Description:** Rust 2015 does not permit the use of `async fn`.
- [ ] [`E0689`](https://doc.rust-lang.org/error_codes/E0689.html)
  - **Error Description:** A method was called on an ambiguous numeric type.
- [ ] [`E0690`](https://doc.rust-lang.org/error_codes/E0690.html)
  - **Error Description:** A struct with the representation hint `repr(transparent)` had two or more fields
that were not guaranteed to be zero-sized.
- [ ] [`E0691`](https://doc.rust-lang.org/error_codes/E0691.html)
  - **Error Description:** A struct, enum, or union with the `repr(transparent)` representation hint
contains a zero-sized field that requires non-trivial alignment.
- [ ] [`E0692`](https://doc.rust-lang.org/error_codes/E0692.html)
  - **Error Description:** A `repr(transparent)` type was also annotated with other, incompatible
representation hints.
- [ ] [`E0693`](https://doc.rust-lang.org/error_codes/E0693.html)
  - **Error Description:** `align` representation hint was incorrectly declared.
- [ ] [`E0695`](https://doc.rust-lang.org/error_codes/E0695.html)
  - **Error Description:** A `break` statement without a label appeared inside a labeled block.
- [ ] [`E0696`](https://doc.rust-lang.org/error_codes/E0696.html)
  - **Error Description:** A function is using `continue` keyword incorrectly.
- [ ] [`E0697`](https://doc.rust-lang.org/error_codes/E0697.html)
  - **Error Description:** A closure has been used as `static`.
- [ ] [`E0698`](https://doc.rust-lang.org/error_codes/E0698.html)
  - **Error Description:** When using generators (or async) all type variables must be bound so a
generator can be constructed.
- [ ] [`E0699`](https://doc.rust-lang.org/error_codes/E0699.html)
  - **Error Description:** A method was called on a raw pointer whose inner type wasn't completely known.
- [ ] [`E0700`](https://doc.rust-lang.org/error_codes/E0700.html)
  - **Error Description:** The `impl Trait` return type captures lifetime parameters that do not
appear within the `impl Trait` itself.
- [ ] [`E0701`](https://doc.rust-lang.org/error_codes/E0701.html)
  - **Error Description:** This error indicates that a `#[non_exhaustive]` attribute was incorrectly placed
on something other than a struct or enum.
- [x] [`E0703`](https://doc.rust-lang.org/error_codes/E0703.html)
  - **Error Description:** Invalid ABI (Application Binary Interface) used in the code.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2519
- [ ] [`E0704`](https://doc.rust-lang.org/error_codes/E0704.html)
  - **Error Description:** An incorrect visibility restriction was specified.
- [ ] [`E0705`](https://doc.rust-lang.org/error_codes/E0705.html)
  - **Error Description:** A `#![feature]` attribute was declared for a feature that is stable in the
current edition, but not in all editions.
- [ ] [`E0706`](https://doc.rust-lang.org/error_codes/E0706.html)
  - **Error Description:** `async fn`s are not yet supported in traits in Rust.
- [ ] [`E0708`](https://doc.rust-lang.org/error_codes/E0708.html)
  - **Error Description:** `async` non-`move` closures with parameters are currently not supported.
- [ ] [`E0710`](https://doc.rust-lang.org/error_codes/E0710.html)
  - **Error Description:** An unknown tool name was found in a scoped lint.
- [ ] [`E0711`](https://doc.rust-lang.org/error_codes/E0711.html)
  - **Error Description:** #### This error code is internal to the compiler and will not be emitted with normal Rust code.
- [ ] [`E0712`](https://doc.rust-lang.org/error_codes/E0712.html)
  - **Error Description:** A borrow of a thread-local variable was made inside a function which outlived
the lifetime of the function.
- [ ] [`E0713`](https://doc.rust-lang.org/error_codes/E0713.html)
  - **Error Description:** This error occurs when an attempt is made to borrow state past the end of the
lifetime of a type that implements the `Drop` trait.
- [ ] [`E0714`](https://doc.rust-lang.org/error_codes/E0714.html)
  - **Error Description:** A `#[marker]` trait contained an associated item.
- [ ] [`E0715`](https://doc.rust-lang.org/error_codes/E0715.html)
  - **Error Description:** An `impl` for a `#[marker]` trait tried to override an associated item.
- [ ] [`E0716`](https://doc.rust-lang.org/error_codes/E0716.html)
  - **Error Description:** A temporary value is being dropped while a borrow is still in active use.
- [ ] [`E0717`](https://doc.rust-lang.org/error_codes/E0717.html)
  - **Error Description:** #### This error code is internal to the compiler and will not be emitted with normal Rust code.
- [ ] [`E0718`](https://doc.rust-lang.org/error_codes/E0718.html)
  - **Error Description:** A `#[lang = ".."]` attribute was placed on the wrong item type.
- [ ] [`E0719`](https://doc.rust-lang.org/error_codes/E0719.html)
  - **Error Description:** An associated type value was specified more than once.
- [ ] [`E0720`](https://doc.rust-lang.org/error_codes/E0720.html)
  - **Error Description:** An `impl Trait` type expands to a recursive type.
  - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2523
- [ ] [`E0722`](https://doc.rust-lang.org/error_codes/E0722.html)
  - **Error Description:** The `optimize` attribute was malformed.
- [ ] [`E0724`](https://doc.rust-lang.org/error_codes/E0724.html)
  - **Error Description:** `#[ffi_returns_twice]` was used on something other than a foreign function
declaration.
- [ ] [`E0725`](https://doc.rust-lang.org/error_codes/E0725.html)
  - **Error Description:** A feature attribute named a feature that was disallowed in the compiler
command line flags.
- [ ] [`E0726`](https://doc.rust-lang.org/error_codes/E0726.html)
  - **Error Description:** An argument lifetime was elided in an async function.
- [ ] [`E0727`](https://doc.rust-lang.org/error_codes/E0727.html)
  - **Error Description:** A `yield` clause was used in an `async` context.
- [ ] [`E0728`](https://doc.rust-lang.org/error_codes/E0728.html)
  - **Error Description:** [`await`] has been used outside [`async`] function or [`async`] block.
- [ ] [`E0729`](https://doc.rust-lang.org/error_codes/E0729.html)
  - **Error Description:** #### Note: this error code is no longer emitted by the compiler
- [ ] [`E0730`](https://doc.rust-lang.org/error_codes/E0730.html)
  - **Error Description:** An array without a fixed length was pattern-matched.
- [ ] [`E0731`](https://doc.rust-lang.org/error_codes/E0731.html)
  - **Error Description:** An enum with the representation hint `repr(transparent)` had zero or more than
one variants.
- [ ] [`E0732`](https://doc.rust-lang.org/error_codes/E0732.html)
  - **Error Description:** An `enum` with a discriminant must specify a `#[repr(inttype)]`.
- [ ] [`E0733`](https://doc.rust-lang.org/error_codes/E0733.html)
  - **Error Description:** An [`async`] function used recursion without boxing.
- [ ] [`E0734`](https://doc.rust-lang.org/error_codes/E0734.html)
  - **Error Description:** A stability attribute has been used outside of the standard library.
- [ ] [`E0735`](https://doc.rust-lang.org/error_codes/E0735.html)
  - **Error Description:** Type parameter defaults cannot use `Self` on structs, enums, or unions.
- [ ] [`E0736`](https://doc.rust-lang.org/error_codes/E0736.html)
  - **Error Description:** `#[track_caller]` and `#[naked]` cannot both be applied to the same function.
- [ ] [`E0737`](https://doc.rust-lang.org/error_codes/E0737.html)
  - **Error Description:** `#[track_caller]` requires functions to have the `"Rust"` ABI for implicitly
receiving caller location. See [RFC 2091] for details on this and other
restrictions.
- [ ] [`E0739`](https://doc.rust-lang.org/error_codes/E0739.html)
  - **Error Description:** `#[track_caller]` can not be applied on struct.
- [ ] [`E0740`](https://doc.rust-lang.org/error_codes/E0740.html)
  - **Error Description:** A `union` was declared with fields with destructors.
- [ ] [`E0741`](https://doc.rust-lang.org/error_codes/E0741.html)
  - **Error Description:** A non-structural-match type was used as the type of a const generic parameter.
- [ ] [`E0742`](https://doc.rust-lang.org/error_codes/E0742.html)
  - **Error Description:** Visibility is restricted to a module which isn't an ancestor of the current
item.
- [ ] [`E0743`](https://doc.rust-lang.org/error_codes/E0743.html)
  - **Error Description:** The C-variadic type `...` has been nested inside another type.
- [ ] [`E0744`](https://doc.rust-lang.org/error_codes/E0744.html)
  - **Error Description:** An unsupported expression was used inside a const context.
- [ ] [`E0745`](https://doc.rust-lang.org/error_codes/E0745.html)
  - **Error Description:** The address of temporary value was taken.
- [ ] [`E0746`](https://doc.rust-lang.org/error_codes/E0746.html)
  - **Error Description:** An unboxed trait object was used as a return value.
- [ ] [`E0747`](https://doc.rust-lang.org/error_codes/E0747.html)
  - **Error Description:** Generic arguments were not provided in the same order as the corresponding
generic parameters are declared.
- [ ] [`E0748`](https://doc.rust-lang.org/error_codes/E0748.html)
  - **Error Description:** A raw string isn't correctly terminated because the trailing `#` count doesn't
match its leading `#` count.
- [ ] [`E0749`](https://doc.rust-lang.org/error_codes/E0749.html)
  - **Error Description:** An item was added on a negative impl.
- [ ] [`E0750`](https://doc.rust-lang.org/error_codes/E0750.html)
  - **Error Description:** A negative impl was made default impl.
- [ ] [`E0751`](https://doc.rust-lang.org/error_codes/E0751.html)
  - **Error Description:** There are both a positive and negative trait implementation for the same type.
- [ ] [`E0752`](https://doc.rust-lang.org/error_codes/E0752.html)
  - **Error Description:** The entry point of the program was marked as `async`.
- [x] [`E0753`](https://doc.rust-lang.org/error_codes/E0753.html)
  - **Error Description:** An inner doc comment was used in an invalid context.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2531
- [x] [`E0754`](https://doc.rust-lang.org/error_codes/E0754.html)
  - **Error Description:** A non-ASCII identifier was used in an invalid context.
  - Thanks @tamaroning 
    - <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 16 16"><path fill="#b2564f" d="M8 9.5a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z"/><path fill="#b2564f" d="M8 0a8 8 0 1 1 0 16A8 8 0 0 1 8 0ZM1.5 8a6.5 6.5 0 1 0 13 0a6.5 6.5 0 0 0-13 0Z"/></svg> https://github.com/Rust-GCC/gccrs/issues/2548
    - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2552
- [ ] [`E0755`](https://doc.rust-lang.org/error_codes/E0755.html)
  - **Error Description:** The `ffi_pure` attribute was used on a non-foreign function.
- [ ] [`E0756`](https://doc.rust-lang.org/error_codes/E0756.html)
  - **Error Description:** The `ffi_const` attribute was used on something other than a foreign function
declaration.
- [ ] [`E0757`](https://doc.rust-lang.org/error_codes/E0757.html)
  - **Error Description:** A function was given both the `ffi_const` and `ffi_pure` attributes.
- [ ] [`E0758`](https://doc.rust-lang.org/error_codes/E0758.html)
  - **Error Description:** A multi-line (doc-)comment is unterminated.
- [ ] [`E0761`](https://doc.rust-lang.org/error_codes/E0761.html)
  - **Error Description:** Multiple candidate files were found for an out-of-line module.
- [ ] [`E0762`](https://doc.rust-lang.org/error_codes/E0762.html)
  - **Error Description:** A character literal wasn't ended with a quote.
- [ ] [`E0763`](https://doc.rust-lang.org/error_codes/E0763.html)
  - **Error Description:** A byte constant wasn't correctly ended.
- [ ] [`E0764`](https://doc.rust-lang.org/error_codes/E0764.html)
  - **Error Description:** A mutable reference was used in a constant.
- [ ] [`E0765`](https://doc.rust-lang.org/error_codes/E0765.html)
  - **Error Description:** A double quote string (`"`) was not terminated.
- [ ] [`E0766`](https://doc.rust-lang.org/error_codes/E0766.html)
  - **Error Description:** A double quote byte string (`b"`) was not terminated.
- [ ] [`E0767`](https://doc.rust-lang.org/error_codes/E0767.html)
  - **Error Description:** An unreachable label was used.
- [ ] [`E0768`](https://doc.rust-lang.org/error_codes/E0768.html)
  - **Error Description:** A number in a non-decimal base has no digits.
- [x] [`E0769`](https://doc.rust-lang.org/error_codes/E0769.html)
  - **Error Description:** A tuple struct or tuple variant was used in a pattern as if it were a struct or
struct variant.
  - <svg xmlns="http://www.w3.org/2000/svg" width="25" height="25" viewBox="0 0 24 24"><path fill="#b174ff" d="M7.105 8.79A3.001 3.001 0 0 0 10 11h4a5.002 5.002 0 0 1 4.927 4.146A3.001 3.001 0 0 1 18 21a3 3 0 0 1-1.105-5.79A3.001 3.001 0 0 0 14 13h-4a4.978 4.978 0 0 1-3-1v3.17a3.001 3.001 0 1 1-2 0V8.83a3.001 3.001 0 1 1 2.105-.04Z"/></svg>  https://github.com/Rust-GCC/gccrs/pull/2564
- [ ] [`E0770`](https://doc.rust-lang.org/error_codes/E0770.html)
  - **Error Description:** The type of a const parameter references other generic parameters.
- [ ] [`E0771`](https://doc.rust-lang.org/error_codes/E0771.html)
  - **Error Description:** #### Note: this error code is no longer emitted by the compiler
- [ ] [`E0773`](https://doc.rust-lang.org/error_codes/E0773.html)
  - **Error Description:** A builtin-macro was defined more than once.
- [ ] [`E0774`](https://doc.rust-lang.org/error_codes/E0774.html)
  - **Error Description:** `derive` was applied on something which is not a struct, a union or an enum.
- [ ] [`E0775`](https://doc.rust-lang.org/error_codes/E0775.html)
  - **Error Description:** `#[cmse_nonsecure_entry]` is only valid for targets with the TrustZone-M
extension.
- [ ] [`E0776`](https://doc.rust-lang.org/error_codes/E0776.html)
  - **Error Description:** `#[cmse_nonsecure_entry]` functions require a C ABI
- [ ] [`E0777`](https://doc.rust-lang.org/error_codes/E0777.html)
  - **Error Description:** A literal value was used inside `#[derive]`.
- [ ] [`E0778`](https://doc.rust-lang.org/error_codes/E0778.html)
  - **Error Description:** The `instruction_set` attribute was malformed.
- [ ] [`E0779`](https://doc.rust-lang.org/error_codes/E0779.html)
  - **Error Description:** An unknown argument was given to the `instruction_set` attribute.
- [ ] [`E0780`](https://doc.rust-lang.org/error_codes/E0780.html)
  - **Error Description:** Cannot use `doc(inline)` with anonymous imports
- [ ] [`E0781`](https://doc.rust-lang.org/error_codes/E0781.html)
  - **Error Description:** The `C-cmse-nonsecure-call` ABI can only be used with function pointers.
- [ ] [`E0782`](https://doc.rust-lang.org/error_codes/E0782.html)
  - **Error Description:** Trait objects must include the `dyn` keyword.
- [ ] [`E0783`](https://doc.rust-lang.org/error_codes/E0783.html)
  - **Error Description:** The range pattern `...` is no longer allowed.
- [ ] [`E0784`](https://doc.rust-lang.org/error_codes/E0784.html)
  - **Error Description:** A union expression does not have exactly one field.
- [ ] [`E0785`](https://doc.rust-lang.org/error_codes/E0785.html)
  - **Error Description:** An inherent `impl` was written on a dyn auto trait.
- [ ] [`E0786`](https://doc.rust-lang.org/error_codes/E0786.html)
  - **Error Description:** A metadata file was invalid.
- [ ] [`E0787`](https://doc.rust-lang.org/error_codes/E0787.html)
  - **Error Description:** An unsupported naked function definition.
- [ ] [`E0788`](https://doc.rust-lang.org/error_codes/E0788.html)
  - **Error Description:** A `#[no_coverage]` attribute was applied to something which does not show up
in code coverage, or is too granular to be excluded from the coverage report.
- [ ] [`E0789`](https://doc.rust-lang.org/error_codes/E0789.html)
  - **Error Description:** #### This error code is internal to the compiler and will not be emitted with normal Rust code.
- [ ] [`E0790`](https://doc.rust-lang.org/error_codes/E0790.html)
  - **Error Description:** You need to specify a specific implementation of the trait in order to call the
method.
- [ ] [`E0791`](https://doc.rust-lang.org/error_codes/E0791.html)
  - **Error Description:** Static variables with the `#[linkage]` attribute within external blocks
must have one of the following types, which are equivalent to a nullable
pointer in C:
- [ ] [`E0792`](https://doc.rust-lang.org/error_codes/E0792.html)
  - **Error Description:** A type alias impl trait can only have its hidden type assigned
when used fully generically (and within their defining scope).
This means
- [ ] [`E0793`](https://doc.rust-lang.org/error_codes/E0793.html)
  - **Error Description:** An unaligned references to a field of a [packed] struct got created.
- [ ] [`E0794`](https://doc.rust-lang.org/error_codes/E0794.html)
  - **Error Description:** A lifetime parameter of a function definition is called *late-bound* if it both:

