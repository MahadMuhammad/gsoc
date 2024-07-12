---
title: "Rust Concepts"
description: "Sharing my daily learning and notes on Rust Concepts"
lead: ""
date: 2024-06-22T20:09:13+05:00
lastmod: 2023-08-22T20:09:13+05:00
draft: false
images: []
menu:
  docs:
    parent: "journey"
    identifier: "rust-learning-b0e729093563de47c17546329c7e65da"
weight: 3
toc: true
type: docs
---

### Contents:

- [Getting Started](#getting-started)
- [Common-Programming-Concepts](#common-programming-concepts)
- [Understanding Ownership](#understanding-ownership)
- [Structs](#structs)
- [Enums](#enums)
- [Packages-Crates-and-Modules](#packages-crates-and-modules)
- [Common-Collections](#common-collections)
- [Error-Handling](#error-handling)
- [Generic-Types-Traits-Lifetimes](#generic-types-traits-lifetimes)
- [Testing](#testing)
- [Functional Language Features](#functional-language-features)
- [Smart-Pointers](#smart-pointers)
- [Fearless-Concurrency](#fearless-concurrency)
- [Object-Oriented-Programming](#object-oriented-programming)
- [Patterns-and-Matching](#patterns-and-matching)
- [Advanced-Features](#advanced-features)
- [Unsafe Rust](#unsafe-rust)

## Common Collections:

- These data structures store' multiple values in one data structure.
- The data is stored on the _heap_.
- Famous common collections are: _vector_, _string_, _hash map_.
- Vector is a dynamic array. We can store different types of data in a vector using enums.
- String: Rust has only one core type which is `str`
  - String is a wrapper of `Vec<u8>` in rust.
  - common methods are `String::from` and `to_string()`.
  - Concatenate strings using `+` or `format!` macro.
  - Growing using `.push_str`
  - TODO: Read this tricky explanation: [String concat function](https://doc.rust-lang.org/book/ch08-02-strings.html#concatenation-with-the--operator-or-the-format-macro)
  - TODO: read explanation of `contains` method and `replace` method in context of strings.
- Hashmaps: It stores key-value pairs. It is implemented using a hash table.
  - By default, rust uses `siphash` algorithm, which is resistant to DoS attacks.

## Error Handling:

- Rust always forces us to handle all error cases.
- Rust groups errors into two types:
  - _Recoverable_: Such as file not found -> Result<T,E>
  - _UnRecoverable_: Such as accessing an invalid index in an array -> panic! macro

### Unrecoverable Error With `Panic`: 
- We can track the line number and file name where the panic occurred.

### Recoverable Error With `Result`:
- `Result` is an enum with two variants: `Ok` and `Err`.
- We can use `match` or `unwrap` to handle the result.
  - `unwrap` will panic if the result is `Err` and Ok otherwise.
  - `expect` is similar to `unwrap` but allows us to specify the panic message.
