---
type: content
tags: [practice]
---
# Test-driven development

Why: test coverage, code quality, finding solutions to hard problems, knowledge sharing

Test-driven development is a way of writing code which puts an emphasis on test coverage, correctness, simplicity and knowledge sharing. Simplicity and correctness are achieved by forcing you to analyze the problem first (in the form of well written tests) before creating a solution. 

The basic process behind this technique is: start by writing test code for a feature or a sub-feature which will fail because the implementation does not satisfy this test. Then add only as much implementation code as necessary in order to make the test pass. After that you can write a test for the next feature or sub-feature and repeat the process until all required features are implement. Ideally, this process helps you to never implement a line of code without writing a test for that line first.

If need be, break up features into easily testable sub-features in order to simplify the test writing process. 
For each test you should also think what the focus of the test is. If implementation code is required in the test which is not within the focus of the test you should consider mocking or stubbing this code.    

When writing tests favor short and easily readable tests, since well written tests can act as a living documentation. 

## Requirements

### Behavior
* Work in small increments (i.e. prefer small tests and implementation changes)
* Always write a failing test first which fails for the right reasons (i.e. a functionality is not implemented)
* Treat test code as documentation: keep it brief but expressive
* Try to be as specific as you can with your tests (good tests can make a solution almost obvious)

### Setup

Since you will run your test suite often consider researching how to run your tests quickly. For most IDEs and code editors there is a keyboard shortcut to do exactly that. Additionally, you might consider test runners which continuously watch your projects files and will run your test suite when certain criteria are matched.
Also, helpful are tools which display the test coverage. This helps to double check whether you wrote implementation code and test code in such a way that you achieved 100% test coverage. 

### Resources

* :book: [Test Driven Development: By Example by Kent Beck](https://www.amazon.com/dp/0321146530/ref=cm_sw_r_cp_ep_dp_BJ0SAbBCVPGBV)
* [Agile Alliance Glossary: Test driven development](https://www.agilealliance.org/glossary/tdd/)
* :gem: [FizzBuzz Kata for learning TDD](http://codingdojo.org/kata/FizzBuzz/)


## Relations

* Pair programming
* Mob programming
* Refactoring

## Take your action

### For novices and beginners:

In order to get a feeling for TDD you should start with a Kata first. In the Kata concentrate on ways to write tests so that the solution becomes obvious. Don't try to solve the whole problem at once, instead break the features up into sub-features. If need be even break up the sub-features into "obvious" steps and write tests for those. For FizzBuzz this could mean that you will start out with a very simple test which just checks whether Fizz is printed out instead of the number 3. You can then add further tests in order to "force" yourself to implement more complex behavior.
Also, take your time to learn the various keyboard shortcuts of your IDEs to run your tests quickly.

Once you feel comfortably with this technique try it out when implementing a simple change to production code. Also, consider to do this change in a pair as a second set of eyes might be helpful to identify issues with overly permissive tests or readability. Additionally, pairing whilst doing TDD might help to spread this technique across your team.

### For experienced:

Use TDD in Pair and Mob programming sessions as a natural role switch mechanism: one person will start writing a failing test and then pass on the keyboard. Then another person will write just enough implementation code to satisfy the test and write the next test. Then another person (in a Mob Programming context) will do the same and so on.

Spend some time thinking about how using TDD influences software design. Are there advantages other than achieving a high test coverage and documenting your code? Are there any disadvantages?

If you haven't try out the [Bowling Kata](http://codingdojo.org/kata/Bowling/) do so.   
