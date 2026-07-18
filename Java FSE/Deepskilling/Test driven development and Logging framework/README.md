# Module 4 - Test Driven Development (TDD) & Logging

## Introduction

This module demonstrates the basics of software testing and application logging in Java. It includes creating unit tests with JUnit, using Mockito for mocking dependencies, and implementing logging with SLF4J and Logback to improve debugging and application monitoring.

## Tech Stack

- Java
- Maven
- JUnit 4.13.2
- Mockito 4.11.0
- SLF4J 1.7.30
- Logback 1.2.3

---

# JUnit Practice

## Exercise 1 - JUnit Project Configuration

- Added JUnit dependency to a Maven project.
- Created and ran the first unit test successfully.

## Exercise 2 - Unit Testing Calculator

- Wrote test cases for calculator methods.
- Checked the correctness of addition and subtraction operations.

## Exercise 3 - Assertion Methods

Applied different assertion techniques provided by JUnit, including:

- `assertEquals()`
- `assertTrue()`
- `assertFalse()`
- `assertNull()`
- `assertNotNull()`

## Exercise 4 - Arrange, Act, Assert Pattern

- Followed the AAA testing approach.
- Initialized test data using `@Before`.
- Performed cleanup with `@After`.
- Validated operations of the `BankAccount` class.

---

# Mockito Practice

## Exercise 1 - Creating Mocks

- Generated mock objects for dependencies.
- Returned predefined responses through stubbing.

## Exercise 2 - Interaction Verification

- Confirmed expected method invocations with `verify()`.

## Exercise 3 - Argument Matchers

- Tested methods using matchers like `anyString()` and similar utilities.

## Exercise 4 - Testing Void Methods

- Mocked methods with no return value.
- Verified their execution.

## Exercise 5 - Consecutive Return Values

- Configured mocked methods to return multiple values using `thenReturn()`.

## Exercise 6 - Method Execution Sequence

- Verified the order of method calls with `InOrder`.

## Exercise 7 - Exception Simulation

- Used `doThrow()` to simulate exceptions.
- Tested application behavior under error conditions.

---

# Logging with SLF4J

## Exercise 1 - Warning and Error Logging

- Integrated SLF4J into the project.
- Produced log messages with WARN and ERROR levels.

## Exercise 2 - Dynamic Log Messages

- Implemented parameterized logging using `{}` placeholders.
- Logged runtime values efficiently.

## Exercise 3 - Logback Configuration

- Configured logging through `logback.xml`.
- Used both `ConsoleAppender` and `FileAppender`.
- Stored logs in the console as well as an external log file.

---

# Skills Gained

After completing this module, the following concepts were practiced:

- Test Driven Development (TDD) fundamentals
- Writing effective unit tests using JUnit
- Mocking dependencies with Mockito
- Verifying interactions between objects
- Configuring application logging with SLF4J and Logback
- Managing log levels and appenders
- Developing reliable, maintainable, and well-tested Java applications

---

## Developer

**Kaushal Kishor**
