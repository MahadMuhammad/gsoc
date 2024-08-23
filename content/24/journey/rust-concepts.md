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

### Unrecoverable Error With Panic:

- We can track the line number and file name where the panic occurred.

### Recoverable Error With Result:

- `Result` is an enum with two variants: `Ok` and `Err`.
- We can use `match` or `unwrap` to handle the result.
  - `unwrap` will panic if the result is `Err` and Ok otherwise.
  - `expect` is similar to `unwrap` but allows us to specify the panic message.
  - In production, use `expect` rather than `unwrap` to provide a meaningful error message.
- _Propagating Errors_:
  - We can use `?` operator to propagate the error to the calling function.
  - The function must return `Result` type to propagate the error.

### To _panic_ or _not to panic_:

- **panic** makes our code unrecoverable
- In prototypes / tests, it's okay to panic.
- If failure is expected, use **Reult** type.

## Generic Types, Traits, Lifetimes:

- Generics enhance code resuability by allowing the same code to operate on different data types.
- We can extract duplicate code into functions.
- And on functions, we can use generics to make them work for more than one concrete type.
- Luckily, we have little run time cost becuase of **monomorphization**.

### Traits: Defining Shared Behavior:

- Learn more about **coherence** and **orphan rules**.
- TODO: Learn about **blanket implementations**.
- By using appostrophe (`'`) we are not changing the lifetime.
  - Rather, we are specfiying rust borrowchecker to reqject the constraints that doesn't satisfy the lifetime.

### Lifetimes:

- TODO: Learn more about **lifetime elision rules**
- Lifetimes on function or method parameters are called input lifetimes, and lifetimes on return values are called output lifetimes.