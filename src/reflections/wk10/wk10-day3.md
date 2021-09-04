# Read Dotnet WebAPI's > Welcome to SQL, and answer the following questions

Today we connected a c# backend to a MySQL database afternoon work: https://github.com/Jaron-Warren/castles_and_knights

## In a SQL table, what is the difference between information in a row and information in a column?

the rows would represent an entire object with all it's properties. A column would be one type of property e.g. "title"

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE characters(
  name VARCHAR(20),
  age int,
  description VARCHAR(255) NOT NULL,
  id int NOT NULL,
);

## What is the difference between the following statements:

DELETE FROM table_name;
DROP TABLE table_name;

Delete from will remove a row where condition is met
Drop table will delete an entire table by name