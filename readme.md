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

## Usage

Start the REPL and type Monkey code:

```
>> let x = 5;
>> return 10;
>> !true
```
