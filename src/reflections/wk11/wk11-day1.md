# Read Foundations of C# > C# Inheritance and answer the following questions

today we learned about many to many relationships in SQL. afternoon work: https://github.com/Jaron-Warren/ContractWork

## What does Inheritance accomplish for us in C#?

two main things: 1. cuts down on redudant code and 2. links classes together so the child can be considered the same thing as the parent in code.

## How does Member inheritance work in C#? Does a class inherit all members of the base class?

 everything in a class EXCEPT Constructors and finalizers transfer.

## How does accessibility affect inheritance?

private classes are restricted, protected ONLY works with children, internal is visible only to classe located in thee same assembly as the parent