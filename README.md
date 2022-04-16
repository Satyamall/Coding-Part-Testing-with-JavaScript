# Coding-Part-Testing-with-JavaScript


# Notes

# Testing with javascript: 

A test case is a document, which has a set of test data, conditions and expected results , developed for a particular scenario in order to verify the code quality and behavior against a specific requirement.

 - It is important as programmers, that we have a better understanding of what the code that we write do.
 - We can speed up our development as we spend less time debugging and are aware of where our code has broken.
 - by writing test cases first, we can follow a test driven development that enforces us to think of edge cases and build better software.

for example:
 - write a test case to verify that a function sum, returns 3, when 1 and 2 are passed into it.

# TDD: 
Test-driven development is a software development process that relies on the repetition of a very short development cycle: requirements are turned into very specific test cases, then the code is improved so that the tests pass.

Automated testing is a key component of continuous integration and continuous delivery and it's a great way to scale your QA process as you add new features to your application.

# The different types of tests:

**Unit tests:** 
Unit tests are the most basic type of testing, close to the source of your application. They consist in testing individual methods and functions of the classes, components or modules used by your software. Unit tests are in general quite easier to automate and can be run very quickly by a continuous integration server.

**Integration tests:** 
Integration tests verify that different modules or services used by your application work well together. For example, it can be testing the interaction with the database or making sure that microservices work together as expected. These types of tests are more expensive to run as they require multiple parts of the application to be up and running.

**End-to-end tests:** 
End-to-end testing replicates a user behavior with the software in a complete application environment. It verifies that various user flows work as expected and can be as simple as loading a web page or logging in or much more complex scenarios verifying email notifications, online payments, etc. Functional tests. Products like cypress.io can be used to do end to end UI testing.

**Other forms of testing:**
 - Acceptance testing
 - Performance testing
 - Smoke testing
 - Penetration Testing
