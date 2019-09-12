---
type: content
tags: practice
---
# Mob Programming

Why: knowledge sharing, finding solutions to hard problems, team building

Mob programming is a natural evolution of pair programming that provides a framework for working as a group on software. There are different modes of operation. One of the simplest mode to get started with, requires one computer, a big screen and three roles. The roles are: A driver (singular), a navigator (singular) and a pool of experts. The driver is the typist and transforms ideas communicated by the navigator into code. The driver does not have any ideas of their own and only listens to what the navigator says. The navigator task is to give the driver high level instructions on how to solve the problem at hand without dictating code. Therefore, the navigator thinks strategially about the problem to be solved (e.g. "In order to implement the new REST API we should create an appropriately named controller"). The driver thinks tactically (e.g. "I need to create a controller with the name FooController that inherents from the RestApi class"). The pool of experts is everyone else in the team who isn't a driver or navigator. The pool of experts can be queried by the navigator whenever the navigator feels help is needed (e.g. the navigator feels stuck). They can discuss what is going on among themselves but can only communicate with the navigator when being asked to.
As with pair programming the roles should rotate regularly. A simple method is to switch roles based on a timer. To get started you might want to randomly choose a driver and a navigator. The rest of the team forms the pool of experts. After 5 Minutes you choose the next driver and navigator. 

## Requirements

### Behavior
* be respectful
* let the navigator solve the problem in their own way
* don't use smartphones during sessions
* take regular breaks 

### Setup

You will need one computer, a big screen in an area where a whole team can work together over a long period of time. Each participant should be able to comfortably see what is being typed on the screen. Therefore, consider to mirror the computer screen onto the big screen and consider to work in presentation mode (i.e. if your IDE supports it) or with bigger fonts. An alarm for switching roles is also helpful.

### Resources

* :book: [Mob Programming: A Whole Team Approach by Wood Zuill and Kevin Meadows](https://leanpub.com/mobprogramming)
* [Agile Alliance Glossary: Mob Programming](https://www.agilealliance.org/glossary/mob-programming)
* :gem: [Also applicable for Mob Programming: Etiquette for Pair Programming
](https://dzone.com/articles/etiquette-for-pair-programming)
* :movie_camera: ?

## Relations

* Pair programming
* TDD