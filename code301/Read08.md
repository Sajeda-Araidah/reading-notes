# What is SQL?
SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users query, manipulate, and transform data from a relational database. And due to its simplicity,
 SQL databases provide safe and scalable storage for millions of websites and mobile applications.

# Relational databases
  relational database represents a collection of related (two-dimensional) tables.

  ##  1: SELECT queries 
  To retrieve data from a SQL database, we need to write SELECT statements, which are often colloquially refered to as querie

  Select query for a specific columns
`SELECT column, another_column, …`
`FROM mytable;`

## Queries with constraints
Now we know how to select for specific columns of data from a table
Select query with constraints

`SELECT column, another_column, …`
`FROM mytable`
`WHERE condition`
    `AND/OR another_condition`
    `AND/OR …;`

|Operator|Condition|

|=, !=, < <=, >, >=|Standard numerical operators|	
|BETWEEN … AND …|Number is within range of two values (inclusive)|
|NOT BETWEEN … AND …|Number is not within range of two values (inclusive)|
|IN (…)|Number exists in a list)|
|NOT IN (…)|Number does not exist in a list|

![pic](https://img2.arabpng.com/20180526/oqt/kisspng-microsoft-sql-server-mysql-database-logo-5b098c6ebad6d7.7316225815273524307653.jpg)


[To Read More :](https://sqlbolt.com/)