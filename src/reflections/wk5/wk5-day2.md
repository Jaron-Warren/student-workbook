# Read Servers with Node/Express > MongoDb Relationships and answer the following questions

today we learned about mongoDB and reprogrammed gregslist for the backend with mongo. afternoon work: https://github.com/Jaron-Warren/gregslist-node

## What are the three types of relationships?

1:1 one to one, 1:N one to many, N:M many to many

## What are the benefits of the traditional linking of relationships instead of Embedding

in one to one it's not preferred. In one to many, it can keep the data seperate and help with server and network performance.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

Performance, keeping record of relationships in data and not deleting too much. depending on the size of each part, it will be beneficial to use different methods to store data.

