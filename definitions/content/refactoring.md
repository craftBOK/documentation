---
category: practice
title: Refactoring
layout: practice
tags: [practice, maintainability]
---

# Refactoring

Origin: William F. Opdyke and Ralph E. Johnson. _Refactoring: An aid in designing application frameworks and evolving object-oriented systems._ In _Proceedings of Symposium on Object-Oriented Programming Emphasizing Practical Applications_ (SOOPPA), September 1990.

Why: Improve maintainability of exisiting code

Refactoring describes the change to the internal structure of a software system without changing its external behavior.
The main goal is to improve a system's maintainability so that it becomes easier to understand and thus easier to change.
The internal structure of software systems - even when originally designed carefully - tends to degrade over time when more and more changes are applied.
Refactoring reverses this decay process by focusing on the internal structure rather than functionality.

A single refactoring is a small and simple change, so the risk of breaking is low.
Each structural change must be guarded by tests ensuring the external behavior does not change.
To achieve a substantial improvement, many single refactorings are applied sequentially.
Typical code smells can be targeted with specific refactorings.

Modern IDEs support a varying number of refactorings.
Tool support should be preferred since it speeds you up and reduces the chance of breaking the code base, e.g. when you rename a field all references to that field will be renamed automatically.

## Requirements

* Solid test coverage (write tests first when they are missing)
* Zero changes to external behavior (never ever mix up refactoring with bug fixing or feature development)

## Resources

* :book: [Refactoring by Martin Fowler with Kent Beck](https://martinfowler.com/books/refactoring.html)
* :bulb: [Refactoring catalog](https://refactoring.com/catalog/)
* :bulb: [Refactoring: clean your code](https://refactoring.guru/refactoring)

## Relations

* TDD
