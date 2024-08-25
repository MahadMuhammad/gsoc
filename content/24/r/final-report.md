---
title: "Report for Rustc Testsuite Adapter"
description: "Final Report for GCCRS Rustc TestSuite Adaptor"
lead: ""
date: 2023-08-22T20:09:13+05:00
lastmod: 2023-08-22T20:09:13+05:00
draft: false
images: []
menu:
  docs:
    parent: "r"
    identifier: "final-report-b0e729093563de47c17546329c7e65d0"
weight: 1
toc: true
type: docs
---

![GCCRS Logo](gccrs-logo.png)

### [Rustc Testsuite Adapter for GCC Rust (GCCRS)](https://summerofcode.withgoogle.com/programs/2024/projects/KVAetUOC)
- Organization: [GNU Compiler Collection (GCC)](https://gcc.gnu.org/)
- Mentors: [Arthur Cohen](https://github.com/cohenarthur/), [Pierre Emmanuel Patry](https://github.com/P-E-P/) and [Thomas Schwinge](https://github.com/tschwinge)
- Student: [Muhammad Mahad](https://github.com/mahadmuhammad)
---

## Description:

This project is the follow-up of the previous Google Summer of Code project [Improving user errors & Error Code Support for GCC Rust Frontend](https://summerofcode.withgoogle.com/archive/2023/projects/PZbjvfZl). We have to adapt a copy of the rustc testsuite to make use of the error code framework implemented in gccrs as part of GSoC 2023. We need to develop a test case runner similar to rustc's one, in order to match error codes and line numbers to the output of gccrs. Specifically, we need to ensure that gccrs is emitting the correct error code consistent with rustc-1.49. This project requires investigating the current test framework of gcc/gccrs (dejagnu) and also the official rustc one. 
The main exact goal of this project is to have access to a tool which enables us to run gccrs on the rustc test cases and assert that we emit the correct error codes/messages w.r.t to their line numbers. Furthermore, the extended deliverable of this project is to integrate this tool in gccrs CI/CD pipeline.

## What was Done:

- Researched the Rust testing framework "[compiletest](https://rustc-dev-guide.rust-lang.org/tests/compiletest.html)" to understand how test cases are organized and Rust processes and executes test cases.
- Learned "Rust" programming language and created a new tool, named [rusttest-to-dg](github.com/Rust-GCC/rusttest-to-dg) to convert the Rust test cases to DejaGnu format.

## Contributions Overview:
### Pull Requests:
For a comprehensive overview of the pull requests I've submitted, visit [pull requests page](https://mahadmuhammad.github.io/gsoc/24/r/pulls/).

### Issues:
To delve deeper into the intricacies of the issues I've engaged with, feel free to explore the dedicated [issue page](https://mahadmuhammad.github.io/gsoc/24/r/issues/).

## Work for the future:

- Write the invocation script for the tool in the rust language.
- Add support for more header directives in the rust test cases.
- Add more error codes and fix ICE issues that are still present in the latest version of currentgccrs.

## Learning Journey:

- Learned a new programming language - Rust and written a tool "rusttest-to-dg" in Rust.
- Learning how to effectively navigate into large and complex codebases.
- Prioritizing progress over perfection. A piece of advice from my mentor, has really helped me to keep moving forward and not get stuck on small details.
- Overall, I have learned a lot about the GCC Rust Frontend and the Rust programming language.

## Acknowledgements:

I am very grateful to the following people who made this project possible and supported me throughout the process. Their expertise, feedback and encouragement were invaluable for me. 
- [Arthur Cohen](https://github.com/cohenarthur/),[Pierre Emmanuel Patry](https://github.com/P-E-P/) and [Thomas Schwinge](https://github.com/tschwinge) for being my amazing mentors and guiding me with their insights and experience.
- And last but not least, [Philip Herron](https://github.com/philberty/) and [Faisal Abbas](https://github.com/abbasfaisal/) for assisting me in my initial contributions.