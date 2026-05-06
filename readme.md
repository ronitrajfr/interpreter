# Monkey Programming Language Interpreter

A Go implementation of the Monkey programming language interpreter, based on the book "Writing an Interpreter in Go" by Thorsten Ball.

## Overview

Monkey is a simple programming language with the following features:
- Integers, booleans, strings
- Arithmetic expressions
- Bindings (let statements)
- Functions
- Built-in functions
- Higher-order functions and closures
- Arrays, hashes, index expressions
- Prefix and infix operators
- Conditionals
- Return statements
- First-class functions

## Project Structure

```
.
├── main.go          # Entry point
├── lexer/            # Lexical analyzer
├── parser/           # Recursive descent parser
├── token/            # Token definitions
├── ast/              # Abstract Syntax Tree nodes
└── repl/             # Read-Eval-Print Loop
```

## Build & Run

```bash
go run main.go
```

## Usage

Start the REPL and type Monkey code:

```
>> let x = 5;
>>
>> let add = fn(x, y) { x + y };
>>
>> add(10, 20);
```