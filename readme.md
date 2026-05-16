# Monkey Programming Language Interpreter

A Go implementation of the Monkey programming language interpreter, based on the book "Writing an Interpreter in Go" by Thorsten Ball.

## Overview

A step-by-step implementation of the Monkey programming language interpreter. This project builds from tokens → AST → evaluated expressions.

## Project Structure

```
.
├── main.go          # Entry point
├── lexer/           # Lexical analyzer (Chapter 1)
├── parser/          # Recursive descent parser (Chapter 2)
├── token/           # Token definitions
├── ast/             # Abstract Syntax Tree nodes
├── evaluator/       # Expression evaluation (Chapter 3)
├── object/          # Object system for evaluator (Chapter 3)
└── repl/            # Read-Eval-Print Loop
```

## Build & Run

```bash
go run main.go
```

## Progress Tracker

### Chapter 1: Lexing

- [x] Token definitions
- [x] Lexer - identifiers & keywords
- [x] Lexer - integers
- [x] Lexer - operators (=, !=, +, -, etc.)

### Chapter 2: Parsing

- [x] AST node definitions
- [x] Parser - let statements
- [x] Parser - return statements
- [x] Parser - identifiers
- [x] Parser - integer literals
- [x] Parser - prefix operators (unary -, !)
- [x] Parser - infix operators (+, -, \*, /, <, >, ==, !=)
- [x] Parser - boolean literals
- [x] Parser - grouped expressions

### Chapter 3: Evaluation

- [ ] Evaluator - integer & boolean expressions
- [ ] Evaluator - string expressions
- [ ] Evaluator - prefix operators
- [ ] Evaluator - infix operators
- [ ] Evaluator - conditionals
- [ ] Evaluator - return statements
- [ ] Evaluator - bindings/environment
- [ ] Evaluator - function literals
- [ ] Evaluator - function calls
- [ ] Evaluator - closures

### Chapter 4: Extending the Interpreter

- [ ] Strings
- [ ] Arrays
- [ ] Hashes
- [ ] Built-in functions (len, puts, first, last, rest, push)
- [ ] Higher-order functions

## Usage

Start the REPL and type Monkey code:

```
>> let x = 5;
>> return 10;
>> !true
```
