# SQL Practice

## Tasks

This prework will introduce you to some of the more common SQL statements and query techniques, allowing you to practice visualizing and querying a relational database.

1. Download the free e-book, Learn SQL, which is an excellent introduction to SQL and relational databases.

[Learn SQL. The Data School by Chartio](https://drive.google.com/file/d/11PSj53qx-rUGF8mThyHIevYkuQKb0zlL/view?usp=sharing)


* Skim the book.

* Save this for later reference.

2. Practice running common SQL commands using the following SQL Bolt tutorials.

* Lessons 1 through 6 - SQL Queries

* Lessons 13 through 18 - Database Management

For each of the tutorial sections:

1. Read the guidance.
2. Complete the exercises.
3. Capture a screen shot of the completed task list.

## SQL Bolt

SQL stands for Structured Query Language

SQL is a search language that allows for information to be retrieved from data bases. Data bases organize data in tables and SQL allows you to retrieve/add/delete information from the selected database.

Conditions are simply statements that are either true or false. The database takes these statements and evaluates them across all the rows as it scans through your tables and only returns the results that are true.

You can also use OR to define multiple WHERE conditions when you care whether not both but at least one of the conditions is true.

You can invert a condition by simply putting the NOT operator in front of it.

``` Operator  Description
 = equal 
< less than 
> greater than 
<= less than or equal 
>= greater than or equal 
!= not equal 
<> not equal (yup, there are two ways)

Operator Description 
LIKE - a string matches a pattern 
ILIKE - case insensitive version of 
LIKE SIMILAR TO - a string matches a regex pattern
```

## SQL Lesson 1: SELECT queries

[Find the title of each film](img/sql-bolt-ex1-title.jpg),
[Find the director of each film](img/sql-bolt-ex1-director.jpg),
[Find the title and director of each film](img/sql-bolt-ex1-title-director.jpg),
[Find the title and year of each film](img/sql-bolt-ex1-title-year.jpg),
[Find all the information about each film](img/sql-bolt-ex1-all.jpg),

## SQL Lesson 1:  2: Queries with constraints

[Find the movie with a row id of 6](img/sql-bolt-ex2-id.jpg),
[Find the movies released in the years between 2000 and 2010](img/sql-bolt-ex2-between.jpg),
[Find the movies not released in the years between 2000 and 2010](img/sql-bolt-ex2-not-between.jpg),
[Find the first 5 Pixar movies and their release year](img/sql-bolt-ex2-5-pixar.jpg),

## SQL Lesson 3: Queries with constraints

[Find all the Toy Story movies](img/sql-bolt-ex3-constraint1.jpg),
[Find all the movies directed by John Lasseter](img/sql-bolt-ex3-constraint2.jpg),
[Find all the movies (and director) not directed by John Lasseter](img/sql-bolt-ex3-constraint3.jpg),
[Find all the WALL-* movies](img/sql-bolt-ex3-constraint4.jpg),

## SQL Lesson 4: Filtering and sorting Query results

[List all directors of Pixar movies (alphabetically), without duplicates](img/sql-bolt-ex4-filter-sorting1.jpg),
[List the last four Pixar movies released (ordered from most recent to least)](img/sql-bolt-ex4-filter-sorting2.jpg),
[List the first five Pixar movies sorted alphabetically](img/sql-bolt-ex4-filter-sorting3.jpg),
[List the next five Pixar movies sorted alphabetically](img/sql-bolt-ex4-filter-sorting4.jpg),

## SQL Lesson 5: Review Simple SELECT Queries

[List all the Canadian cities and their populations](img/sql-bolt-ex5-select-review1.jpg),
[Order all the cities in the United States by their latitude from north to south)](img/sql-bolt-ex5-select-review2.jpg),
[List all the cities west of Chicago, ordered from west to east](img/sql-bolt-ex5-select-review3.jpg),
[List the two largest cities in Mexico (by population)](img/sql-bolt-ex5-select-review4.jpg),
[List the third and fourth largest cities (by population) in the United States and their population](img/sql-bolt-ex5-select-review5.jpg),

## SQL Lesson 6: Multi-table queries with JOINs

[Find the domestic and international sales for each movie](img/sql-bolt-ex6-joins1.jpg),
[Show the sales numbers for each movie that did better internationally rather than domestically](img/sql-bolt-ex6-joins2.jpg),
[List all the movies by their ratings in descending order](img/sql-bolt-ex6-joins3.jpg),

## SQL Lesson 13: Inserting rows

Schema is a table in a database as a two-dimensional set of rows and columns, with the columns being the properties and the rows being instances of the entity in the table. In SQL, the database schema is what describes the structure of each table, and the datatypes that each column of the table can contain.

## Inserting new data

When inserting data into a database, we need to use an INSERT statement, which declares which table to write into, the columns of data that we are filling, and one or more rows of data to insert. In general, each row of data you insert should contain values for every corresponding column in the table. You can insert multiple rows at a time by just listing them sequentially.

[Add the studio's new production, Toy Story 4 to the list of movies (you can use any director)](img/sql-bolt-ex13-insert1.jpg),
[Add the studio's new production, Toy Story 4 to the list of movies (you can use any director)](img/sql-bolt-ex13-insert2.jpg),
