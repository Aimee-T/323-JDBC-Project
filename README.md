# 323 JDBC Project
With the ease of communications that we enjoy today, it is much easier to collaborate on writing a book than ever. It is so easy in fact, that many authors have formed "writing groups". Each writing group has a unique name and a head writer.
You will form groups of two for this project. Your project should allow for interaction with the user so the user may specified the required data.

![writinggroups](https://user-images.githubusercontent.com/9468502/31323112-6ba71a90-ac57-11e7-94bf-13a164811bb7.jpg)
![writinggroupsrelscheme](https://user-images.githubusercontent.com/9468502/31323131-f0509fd2-ac57-11e7-806c-951996946aa6.jpg)

## TO DO
* Create a .sql file for the DDL and run this script to create the database, tables, etc.
* Write a JDBC program to support the following functions:
  * List all writing groups
  * List all the data for a group specified by the user
  * List all publishers
  * List all the data for a pubisher specified by the user
  * List all book titles
  * List all the data for a book specified by the user. 
  * This includes all the data for the associated publisher and writing group.
  * Insert a new book
  * Insert a new publisher and update all book published by one publisher to be published by the new pubisher.
  * This requirement is two separate operations. The idea is that a new publisher, (xyz) buys out an existing publisher (abc). After the new publisher is added to the database, all books that are currently published by abc will now be published by xyz. 
  * Since this requirement is two parts and the second part cannot be executed without successful completion of the first part, you will need to enclose both parts in a transaction.
  * Remove a book specified by the user
* For all queries involving user input, you must use prepared statements
* You must be able to prove your results after each query
* Make sure to validate the data either through the java code or database constraints
* Make sure you handle any SQLExceptions that are thrown
* Use must use your NetBeans/Derby database for this project
* Make sure you have enough sample data to properly demonstrate your project
* The data can be fictional but it must be meaningful. I don't want to see Book One, Book Two, etc.

## Deliverables

Printed copy of Java code written to support this project

Printed copy of DDL used to create the tables, keys and other constraints

Printed copy of Examples of the output for each query stated above.

Demonstration of all project functionality by both team members.
