# minigrep

A command-line search tool written in Rust, following the final project from Chapter 12 of [The Rust Programming Language](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) book.

## Overview

`minigrep` is a simple implementation of a grep-like utility that searches for a query string in a file and displays matching lines. This project demonstrates core Rust concepts including:

- Command-line argument parsing
- Reading files
- Error handling
- Writing reusable code with functions and modules
- Working with the standard library

## Usage

```sh
minigrep <query> <filename>
```

Example:
```sh
minigrep "search term" poem.txt
```

## Building

```sh
cargo build --release
```

## Running Tests

```sh
cargo test
```

This project is based on Chapter 12 of [The Rust Programming Language](https://doc.rust-lang.org/book/ch12-00-an-io-project.html) book and serves as a hands-on practice for fundamental Rust concepts.
