# Read Foundations of C# > C# Data Types and answer the following questions

Today we were introduced to C# and .net, afternoon work: https://github.com/Jaron-Warren/rock-paper-scissors

## What are the three categories of data types? How are they different?

- Value type: any datatype that holds a value in memory for itself. important: (When you pass a value-type variable from one method to another, the system creates a separate copy of a variable in another method. If value got changed in the one method, it wouldn't affect the variable in another method.)

- reference type: contains a pointer in memory to another location in memory with a value. Default value is null

- pointer type: a pointer to other values

## What are the Value-type data types? What differences do you notice from JavaScript?

The following data types are all of value type:
bool
 byte
 char
 decimal
 double
 enum
 float
 int
 long
 sbyte
 short
 struct
 uint
 ulong
 ushort

## In your own words how do Reference types get stored in memory? How does this differ from Value types?

ontains a pointer in memory to another location in memory with a value. Reference types can be changed across methods.