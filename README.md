# Diego Cordova

Computer engineering student focused on programming languages, compiler construction, runtime systems, and JVM-based virtual machine design.

Currently developing **Eidos**, a multiparadigm programming language with an explicit static type system and a custom stack-based VM designed for language experimentation, semantic analysis, and efficient bytecode execution.

## Areas of Interest

* Programming language design
* Compilers and interpreters
* Virtual machines and bytecode execution
* Runtime systems
* Type systems and semantic analysis
* Software architecture and developer tooling

## Technologies

**Languages**  
Java · Scala · Python

**Tooling**  
Gradle · Maven · Git · Docker · IntelliJ IDEA · JVM

**Currently studying**  
Compiler design · Parsing · Semantic analysis · Runtime optimization · VM architecture

---

# Projects

## Eidos Language

Repository:  
[Eidos Language](https://github.com/DiegoCordova7/eidos-lang)

A multiparadigm programming language featuring:

* Explicit static typing
* Lexical scoping
* Mutability control
* Modular AST architecture
* Semantic analysis
* Bytecode compilation
* Extensible compiler pipeline

Pipeline architecture:

Lexer → Parser → Semantic Analyzer → Compiler → VM

---

## Eidos VM

Repository:  
[Eidos VM](https://github.com/DiegoCordova7/eidos-vm)

A stack-based virtual machine written in Java for executing Eidos bytecode.

Features:

* Stack-based execution model
* Heap memory and lexical scopes
* Modular opcode/instruction system
* Structured control flow
* Program builder APIs
* Designed for future optimization and JIT experimentation

---

## Eidos API

Repository:  
[Eidos API](https://github.com/DiegoCordova7/eidos-api)

REST API built with Spring Boot for executing Eidos programs through the language engine and virtual machine.

Features:

* HTTP-based code execution
* Integration with Eidos Lang Engine and VM
* Runtime metrics collection
* Prometheus/Grafana observability support
* Modular service architecture
* Execution profiling and monitoring

Architecture:

Client → API → Lang Engine → VM

---

## Current Goals

* Expand Eidos semantic analysis
* Add first-class functions and functional pipelines
* Improve runtime metrics and observability
* Develop IDE-oriented tooling
* Increase test coverage and documentation

---

## Contact

📧 [cordovadiegoemilio@gmail.com](mailto:cordovadiegoemilio@gmail.com)
