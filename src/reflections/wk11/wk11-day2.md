# Read Dotnet WebAPI's > Relationships, and answer the following questions

we reviewed for the final today. I practiced white board challenges in the afternoon. problem I was given by tim: https://github.com/Jaron-Warren/whiteboards

## What is the difference between a primary key and a foreign key

the primary key exsists on the parent and the foreign key exsist with the child. The foriegn key refrences back to the primary key's location in a table.

## What is an Alias?

a shorthand writing for a full name of a table. declared in sql statements to avoid writing out the full name

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

SELECT
b.*
dp.id as doctorPatientId
FROM doctorPatients dp
JOIN patients p ON p.id = dp.patientId
WHERE doctorId = doctor

<!-- CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctorPatients (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
) -->