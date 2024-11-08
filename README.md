# SQL-FOR-DATA-ANALYST
Where my sequel query begins lets dive into it

SQL Stands for structured Query Language, Is used for storing and managing dta in relational database Management System System(RDBMS). It enables a user to relate database and tables.
-All the RDBMS like MySQL, PostgreSQL, MS Access and SQL Server use SQL as their standard data base language.
-It allows user to query the database in a number of ways ,using Enlish like statement.


These are my SQL codes showing various SQL queries executed by me on my LITA Database
CREATE TABLE
CREATE TABLE Employee (
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
