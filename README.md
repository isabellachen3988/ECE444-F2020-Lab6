# ECE444-F2020-Lab6

## Pros and cons of TDD:

Pros
1) Allows architectural problems to surface earlier by ensuring that your code is modularized (code has to be modularized to be testable). Interfaces will be clean enough to be tested.

    For example, to implement unit tests, you must make sure that your code is separated properly in functions instead of one giant chunk.

2) Helps you to document and understand your code and is usually up to date since you will be most likely updating the test if functions change.

    For example, whenever you add a testing function, you will most likely add a comment about what that test is testing. Since this is updated regularly, you can refer to this to know exactly what this portion of the code does.

3) Helps to maintain and refactor your code by letting you know what that portion of code is supposed to return

    For example, if you decide to change a function, you can test what the function returns and test so that it will return the same thing after you refactor that function.

4) Easily detect and prevent defects by showing how and where the code may not be what you expect

    For example, you can expect an output at your test but if you don't get what you expect, you know that your code is not functioning as intended.

Cons
1) Takes time. Tests are: maintained regularly, hard to learn and may have large tests

    For example, every time you refactor a function you must maintain the test to ensure that the test still passes. These tests can be hard to learn and require time to research and implement into the projects. Also, if you are writing tests beyond the unit-test level, you must ensure that all parts can run and work with the test. Tests like Puppeteer must be set up in a specific way.

2) Maintenance has to be agreed upon with the whole team, or else the implementation of tests are not very useful

    For example, if one teammate updates the test and the other teammates do not, then the teammates can commit code that does not pass the tests. When the teammate that updates the tests pulls the new code, they will see many errors and do not know where they emerged from.

3) Set up may be difficult

    For example, if you were to create a test for some repository that has not been maintained in a long time, just setting up the test requires you to read over all the interconnected functions and find a way to modularize each portion. This can be draining, and as with the first point, will take a lot of time.
