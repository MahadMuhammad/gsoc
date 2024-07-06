---
title: "Rustc TestSuite Adaptor for GCCRS"
description: "Daily Learning and Notes for a Command Line Application in Rust"
lead: ""
date: 2024-06-22T20:09:13+05:00
lastmod: 2024-06-22T20:09:13+05:00
draft: false
images: []
menu:
  docs:
    parent: "journey"
    identifier: "daily-cli-a0e729093563de47c17546329c7e65da"
weight: 2
toc: true
type: docs
---

- Build list of things to translate to dejagnu directives:
    - `ERROR`
    - `//~^`, `//~|`, `//~`
    - `@edition:2018`

- First step would be to have a tool that translates `//~ ERROR` to `// dg-error`
- Repo link: https://github.com/Rust-GCC/rusttest-to-dg

Some rust open source cli projects for reference:
- [ripgrep](https://github.com/BurntSushi/ripgrep)


### Questions:
- Currently, dejangu ignores the error code in the output. How can we make it check for the error code?
- Can we use clap for parsing the command line arguments?
- We cannot merge the testcases in the master, because rustc and gccrs has different error messages?
- What's the differenece between "&str" amd "&String" in Rust?
