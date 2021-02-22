# Day 4
__02/18/21__

## In a SQL table, what is the difference between information in a row and information in a column?

Each row is an input into the table, an object that is stored. While each colum is the data type, like name, age, and color if you were storing information on a cat.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, and description as strings and an int id.

CREATE TABLE characters
(
id INT AUTO_INCREMENT,
name VARCHAR(255),
age INT NOT NULL,
description VARCHAR(255)
);

## What is the difference between {DELETE FROM tableName;} and {DROP TABLE tableName;} 

DELETE FROM TABLE will remove items from the table, not unlike the findOneAndRemove() from Mongoose. Whereas DROP TABLE will outright delete (or drop) the entire collection! The first one is practically useful while the second is a dangerous command that we actually have to prevent malicious users from invoking, which we do through dapper.

## Afternoon Challenge

https://github.com/Chase16Rogers/burger-shack-api