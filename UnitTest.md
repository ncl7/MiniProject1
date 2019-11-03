# Unittest

Like the unit testing framework in Java, Python has it’s owned called **unittest**. Unittest is a testing framework that supports: test automation, setup and shutdown code for tests, aggregation of tests into collections, and independence of tests. The components of a unittest are the following:

1. **Testcase**: created with unittest.Testcase.
1. **Test**: individual tests are defined when methods start with test. This lets the test runner know which methods will be tested.
1. **assertEqual()**: checks an expected result to verify its condition
1. **setup() and teardown()**: allow to define instructions to be executed before and after each test method.
1. **unittest.main()**: is a command-line interface to the test script. It will produce an output of whether the test passed or failed.

![Unittest](/images/images/unittest.png)
*An example of Unittest file in Python*

