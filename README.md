# Test-driven-development-Jest
Repo for my notes and projects while learning jest



Definitions
Assertion
to state something confidently and forcefully. This means stating an 'is-ness'; 'This is WRONG'. This then equates to a boolean, is it true or false? true would mean a passing test
Interface
a part of software or hardware that facilitates communication
Unit test
focus on one part of the software. A unit test can be run in isolation - it must not rely on the state of any previous tests
Regression testing
running existing tests to ensure that software is working after a change
Integration test
modules, functions etc tested as a group
Stub
a common test helper (could be a database connector, api endpoint) providing hard coded answers
Spy
similar to stub, they record information they were called with
Mock
mimic exactly the object they are replacing, returning specific responses. More than just a stub
Performance test/Load test
measuring how well code copes with stress
Code coverage
measures how many times a line, statement, branch (if/else) or function etc is executed
E2E (end to end) testing
testing a user journey through software from start to achieving the journeys goal
Why Test Driven Development? Most companies seek people with TDD skills, why is this? TDD does not mean 'your code has tests'. It doesn't really mean you have 'experience of using X testing library'. It means you actually write your tests first and write code to pass those test systematically.

What teams actually want from a prospective engineer is:

ability solve a problem in a systematic way
produce clean code
produce code which communicates to the next developer (which could also be you) exactly what the problem was
The TDD technique helps to achieve all of the above.

Technique
Test Driven Development is a technique. A tool is something that makes your life easier. A technique is how to best use the tool. The tool is the assertion library and testing framework.

Rules for test driven development are:

write a failing test
write code to pass the test
refactor (remove duplication)
This is the base for the three laws of TDD:

You are not allowed to write production code unless it is to make a failing unit test pass
You are not allowed to write any more of a unit test than is sufficient to fail; not compiling is failing
You are not allowed to write more production code than is sufficient to pass the one failing unit test
Why fail first?

to see regression tests fail (no 0 positives)
it makes you think about your code
your code will be testable (you don't want to write code then have to refactor in order to be able to test)
