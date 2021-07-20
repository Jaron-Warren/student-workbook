# Read Asynchronous Code > Callback Hell and answer the following questions

Today we learned about API access using the get command and asynchronous code using async and await afternoon work: https://github.com/Jaron-Warren/OPEN_Trivia

## What are some of the signs and causes of Callback Hell?

Callback Hell is caused by writing big continuous functions and not breaking up code into smaller parts. Making smaller functions with single responsibilites is better.

## What does the asynchronous mean and how are callbacks involved?

asynchronous means code is run without stopping for something else to finish after it gets kicked off. Callbacks can be inserted to functions to be ran when the process is complete (callbacks are themselves functions)

## Summarize the 3 ways to avoid / fix Callback Hell

shallow code: one task per function and name your functions! 
modularize: seperate code with files and good names 
Handle every single error: assume errors will happen and code for the error first.