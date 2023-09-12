# dictionary

* JSON (Javascript Object Notation) provides a data interchange format that represents the particular information of an object in a format that you can easily read and understand. e.g.

{
  "id": 99,
  "amount": 123.45
}

https://www.json.org/json-en.html


* we'll write tests before implementing the application code. This is called test driven development (TDD). When the tests pass, you have a working implementation (the application code), and a guard against introducing errors in the future (the tests).

* Testing pyramid:

* Unit Tests: A Unit Test exercises a small “unit” of the system that is isolated from the rest of the system. They should be simple and speedy. You want a high ratio of Unit Tests in your testing pyramid as they’re key to designing highly cohesive, loosely coupled software.

* Integration Tests: Integration Tests exercise a subset of the system and may exercise groups of units in one test. They are more complicated to write and maintain, and run slower than unit tests.

*End-to-End Tests: An End-to-End Test exercises the system using the same interface that a user would, such as a web browser. While extremely thorough, End-to-End Tests can be very slow and fragile because they use simulated user interactions in potentially complicated UIs. Implement the smallest number of these tests.

THE RED, GREEN, REFACTOR LOOP 

Red: Write a failing test for the desired functionality.
Green: Implement the simplest thing that can work to make the test pass.
Refactor: Look for opportunities to simplify, reduce duplication, or otherwise improve the code without changing any behavior—to refactor.
Repeat!
