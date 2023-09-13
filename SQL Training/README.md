# Relational Databases and SQL (Structured Query Language)
![Alt text](image.png)

A database is an organized collection of structured information, typically stored in the form of tables (rows & columns). Relational databases allow storing and retrieving different kinds of related information e.g. products, customers, and orders for an online shopping site. Structured Query Language or SQL (pronounced "sequel") is the most widely used language for interacting with relational databases, and is an essential skill for Data Science professionals.

The following topics are covered in this learning tutorial:

* Use cases and design of relational databases and SQL
* Setting up a database locally using MySQL server
* Creating, modifying and deleting databases and database tables
* SQL Data types and constraints (primary key, foreign key)
* CRUD (Create, Read, Update and Delete) operations on tables
* Exporting and importing data from relational databases

## Problem Statement
We'll learn about relational database and SQL by working through the following [problem](https://www.mysqltutorial.org/mysql-sample-database.aspx)

    QUESTION: Classic Models Inc. is a manufacturer of small scale models of cars, motorcycles, planes, ships trains etc. Products manufactured by Classic Models are sold in toy & gift stores around the world. Here's a small sample of their [products](https://www.tinytown.in/)
    ![Alt text](image-1.png)

    Classic Models has offices around the world with dozens of employees. The customers of Classic Models are typically toy/gift stores. Each customer has a designated sales representative (an employee of Classic Models) they interact with. Customers typically place orders requesting several products in different quantities and pay for multiple orders at once via cheques.
    
    Create a database to record and manage all of the above information. The database will also be used for day-to-day operations (adding customers, placing orders, recording payments, hiring employees etc.).

## Relational Databases
There are many ways of storing data on a computer (text files, JSON files, CSV files, spreadsheets etc.). A relational database is a data storage system with the following properties:
1. Data is stored in tables e.g., customers, products, offices, employees, etc..
2. Each table has a set of columns. Each column is used to store a specific type of data.
3. Data is stored as rows (also called records) within database tables.
4. Tables support CRUD operations on rows: Create, Read, Update and Delete
5. Table can be connected to other tables using relationship constraints (e.g. an employee works at a specific office).
6. Information can be retrieved from the database using the Structured Query Language (SQL)
7. Databases can be hosted locally (on your computer) or on the cloud, for distributed access.

Here's what a table in a relational database looks like:
![Alt text](image-2.png)


## Entity Relationship Diagrams
While setting up a relational database, it's common to create an "Entity Relationship Diagram" (ERD) to describe all the tables within the database and the relations between them. ERDs can be created using drawing tools like [LucidChart](https://www.lucidchart.com/pages/how-to-draw-ERD). Here's the ERD for the Classic Models database:
![Alt text](image-3.png)

## SQL (Structured Query Language)
Structured Query Language or SQL is a programming language for interacting with relational databases. Unlike general purpose programming languages like Python, Java, C++ etc., SQL has a very limited syntax.
![Alt text](image-4.png)

### 
