# Read Working In a Professional Environment > Testing in Vue and answer the following questions

capstones. changed from github branches with name to branches named for feature. closing branches when done.

## What are the three main types of testing we can accomplish in Vue? What does each method provide?

Unit testing - test a unit of code. framework agnostic, must include assertion library providing context for test failure.
component testing -in order to test component it must be mounted to DOM, must be compatible with framework, tests whole component
End-to-End(E2E) testing - test entire application, can take a long time to run historically but can be hot test now.

## What testing method do you think is the most useful? Why?

I would say unit testing because it's simple, universal in scope, customizable.

## What testing method do you think is the least useful? Why?

component testing, it's specific to a framework and doesn't cover anything unit testing can't 