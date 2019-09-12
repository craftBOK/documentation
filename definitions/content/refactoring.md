---
category: practice
tags: []
---

# Refactoring

Origin: William F. Opdyke and Ralph E. Johnson. _Refactoring: An aid in designing application frameworks and evolving object-oriented systems._ In _Proceedings of Symposium on Object-Oriented Programming Emphasizing Practical Applications_ (SOOPPA), September 1990.

Why: Improve maintainability of exisiting code

Refactoring describes changes to the internal structure of software without changing its external behavior.
The main goal is to improve a system's maintainability so that it becomes easier to understand and thus easier to change.
The internal structure of software systems - even when originally designed carefully - tends to degrade over time when more and more changes are applied.
Refactoring reverses this decay process by focusing on the internal structure.

A single refactoring is a small and simple change, so the risk of breaking is low.
Each structural change must be guarded by tests ensuring the exeternal behavior does not change.
To achieve a substantial improvement, many single refactorings are applied sequentially.
Typical code smells can be tackled with specific refactorings.

## Requirements

* Tests, tests, tests

## Resources

* :book: [Refactoring by MArtin Fowler with Kent Beck](https://martinfowler.com/books/refactoring.html)
* :bulb: [Refactoring catalog](https://refactoring.com/catalog/)
* :bulb: [Refactoring: clean your code](https://refactoring.guru/refactoring)

## Relations

* TDD
