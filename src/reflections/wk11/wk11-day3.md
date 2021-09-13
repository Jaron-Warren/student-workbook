# Read Dotnet WebAPI's > SQL Injection, and answer the following questions

Today we were in class and building a full stack app with Mark all day!

## What is SQL injection?

SQL injection is a type of attack that can give an attacker control over your web application database by inserting SQL code into a database query.

## What are 3 methods SQL injection can be done by?

1. If the web application fails to sanitize user input in forms or other inputs, an attacker can inject SQL of their choosing into the back-end database and delete, copy, or modify the contents of the database.
2. An attacker can also modify cookies to poison a web application's database query. A malicious user, or malware, can modify cookies to inject SQL into the back-end database.
3. Server variables such as HTTP headers can also be used as a SQL injection attack vector. Forged headers containing arbitrary SQL can inject that code into the database if the web application fails to sanitize those inputs as well.

## How can we detect and sanitize SQL injection attacks?

Sanitizing requires developers to whitelist input validation (not blacklisting), to use prepared statements with parameterized queries, and to escape all user-supplied input. Also limit account privileges. Assume a breach. What if a developer fails to sanitize a single user input field? Limit the account privileges of the database user. The principle of least privilege applies here. Give the web application the minimum privileges it needs to run.