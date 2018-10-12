# CS258 Software Testing: How to Make Software Fail

## I. Domains, Ranges, Oracles, and Kinds of Testing

How to think about the different elements of software testing.

Lession 1: What is Testing?

Overview of testing
First: Dont see testing is a big problem, even big product is still have bug.
Second: Dont make testing become monotithic problem, but rather can be broken down into a lot of **smaller sub-problems**, and by looking at those sub-problems, we can apply known **techniques** and things that people have done before, and we could sort of pattern match on these problems, and once we've become good at these smaller problems, then we can become much better testers as a whole.

What is testing?
Source of test uinput
Software under test
outputs are processed by an acceptability check

Facts about testing:
The goal of testing isn't so much as finding bugs, but rather it's **finding bugs as early as possible**.
( We dont give product to customer and let them find bugs, it huge cost associated.
We rather than want to find early
And found earlier is cheaper to fix )
The second fact is that it's possible to spend a lot of time and effort on testing and still do a really bad job. Doing testing right requires some **imagination and some good taste**.
Third, **more testing is not always better**. In fact, the quality of testing is all about the cost/benefit tradeoff.
And fundamentally, testing is an economic activity.
( We're spending money or we're spending effort on testing in order to save ourselves money and effort later.
)
Fourth, testing can be made much easier by **designing software to be testable**.

Fifth, **quality cannot be tested into software**.
(And the corollary of that is--it is surprisingly easy to create software but it's impossible to test effectively at all.)

Finally, this is an important one, **testing your own software is really hard** 
( there are several reasons
for this--first of all, it's pretty common for us as developers to be proud of our work.
What that means is we may not really want our own software to fail.
The second reason that testing our own software is hard is that as an individual developer
The third reason is we can't test the code that we left out because we didn't understand that it needed to be written.
Finally, we can't write effective test cases for parts of the spec that we didn't understand correctly.
)

What Happens When We Test Software
( flow after test fail )
Bug in software under test
Bug in acceptability test
Bug in specification
Bug in OS / compiler / lib / hardware

Fixed Sized Queue

Problem set: Black box testing


Lession 2: Problem set: Black box testing


## II. Code Coverage

How to find parts of a program that need more testing.

Lession 3: Coverage
Lession 4
Lession 5
Lession 6
Lession 7
Lession 8
Lession 9
Lession 10

## III. Random Testing

How to automatically generate test cases that break code in unexpected ways.

## IV. Advanced Random Testing

How to engineer a sophisticated random test case generator.

## V. Consequences

How to deal with lots of bugs, how to take a big input that triggers a bug and make it smaller, how to report a bug, and more!

## VI. Conclusion