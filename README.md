# CS258 Software Testing: How to Make Software Fail

## I. Domains, Ranges, Oracles, and Kinds of Testing

How to think about the different elements of software testing.

**Lession 1: What is Testing?**

Overview of testing: testing mindset

- First: Dont see testing is a big problem, even big product is still have bug.
- Second: Dont make testing become monotithic problem, but rather can be broken down into a lot of **smaller sub-problems**, and by looking at those sub-problems, we can apply known **techniques** and things that people have done before, and we could sort of pattern match on these problems, and once we've become good at these smaller problems, then we can become much better testers as a whole.

What is testing?

- Source of test uinput
- Software under test
- outputs are processed by an acceptability check

Facts about testing:

- The goal of testing isn't so much as finding bugs, but rather it's **finding bugs as early as possible**. ( We dont give product to customer and let them find bugs, it huge cost associated. We rather than want to find early and found earlier is cheaper to fix )
- The second fact is that it's possible to spend a lot of time and effort on testing and still do a really bad job. Doing testing right requires some **imagination and some good taste**.
- Third, **more testing is not always better**. In fact, the quality of testing is all about the cost/benefit tradeoff. And fundamentally, testing is an economic activity. ( We're spending money or we're spending effort on testing in order to save ourselves money and effort later.)
- Fourth, testing can be made much easier by **designing software to be testable**.
- Fifth, **quality cannot be tested into software**. (And the corollary of that is--it is surprisingly easy to create software but it's impossible to test effectively at all.)
- Finally, this is an important one, **testing your own software is really hard**. There are several reasons for this:
  - first of all, it's pretty common for us as developers to be proud of our work.
  - What that means is we may not really want our own software to fail.
  - The second reason that testing our own software is hard is that as an individual developer
  - The third reason is we can't test the code that we left out because we didn't understand that it needed to be written.
  - Finally, we can't write effective test cases for parts of the spec that we didn't understand correctly.

What Happens When We Test Software ( flow after test fail )

- Bug in software under test
- Bug in software under test
- Bug in specification
- Bug in OS / compiler / lib / hardware

Fixed Sized Queue

Problem set: Black box testing

10; Creating testable software ~ Things you should care when create new software

- Clean code
- Refactor
- Have describe what module does & how it interacts with other component
- No extra thread
- No global variables
- No pointer soup
- Have unit test
- support fault injection
- contain large number assertions

11; Assertions

Assertions is excutable check validate of value

Example: assert input < 0, assert result > 0

Tips to use assert:

- Assert not for handling error
- Don't make side effice
- No silly assertions

12; Quiz: Checkrep

13; Why Assertions

- Make code self-checking, leading effect testing
- Make code fail early, close to debug
- Assign blame
- Document assumtion, help other developer understand

14; Are Assertions use for production?

This used in production at GCC, LLVM

15; Disabling Assertions

Advantages of disabling assertions

- Code run faster
- Code keep going

Disavantages

- what if code rely on side effect assetion
- even production code, may be better fail early

16; When to use assetion

- Use assetion when accept error in assetion for fulture
- Dont assetion in production to keep aplication going when get error (spaceship problem)

17;18;19;20;21 Create good test case

Sitution for test

22; Testing a GUI

23; 24; APIs trusted

25; 26; 27 Test ting Timing

28;

29; Nonfunction input

30; 31; 32; 33; 34 Types of testing

- white box testing
- black box testing
- unit testing
- integration testing
- system testing
- differential testing
- stress testing
- random testing
- regression testing
- validation testing

**Lession 2: Problem set: Black box testing.**

File

## II. Code Coverage

How to find parts of a program that need more testing.

Lession 3: Coverage

2; 3; 4; 5; Coverage

6; 7; 8; Splay tree

9; 10; Improve coverage

10; 11; 12; Coverage Metrics

- Tesing Coverage
- Fooling Coverage


Lession 4

## III. Random Testing

How to automatically generate test cases that break code in unexpected ways.

Lession 5
Lession 6

## IV. Advanced Random Testing

How to engineer a sophisticated random test case generator. Random testing in practice

Lession 7
Lession 8

## V. Consequences

How to deal with lots of bugs, how to take a big input that triggers a bug and make it smaller, how to report a bug, and more!

Lession 9
Lession 10

## VI. Conclusion