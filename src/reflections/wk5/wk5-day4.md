# Read Servers with Node/Express > Virtuals in Mongoose and answer the following questions

Today we learned about auth0 and integrating it to server and client. for the afternoon we planned for hackathon.

## What is a virtual property?

an additional field for a given model. if a model had a first name and last name field, a virtual could be full name. Virtual properties do not exsist in the database, they are created when called.

## When might you use a virtual property?

when you need additional functionality with a schema, like combining or removing properties when you call an object.

## How do you search by a virtual properties value?

virtuals are not available for document queries or field selection. they only work with get or set.