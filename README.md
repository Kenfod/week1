Week 1 Assignment
Database Design 
Data vs. Information

Section A: Definitions
1.Definition of the below key terms related to databases:

1.1.1.Database
A database is an organized collection of structured information, or data, typically stored electronically in a computer system.

1.1.2.Table
A table is a fundamental structure in a relational database. It represents a collection of related data organized in rows and columns. Tables are used to store and organize data in a structured format.

1.1.3.Record
A record, also known as a row, is a single instance of data stored in a table. It contains a set of values representing the attributes or fields defined by the table's schema. Each record typically corresponds to a unique entity or object being represented in the database.
1.1.4.Field

A field, also known as a column, is a single piece of data within a record that corresponds to a specific attribute or characteristic of the entity being stored in the table. Fields define the structure of the data within a table and specify the type of data that can be stored in each column, such as text, numbers, dates, or binary data.
1.1.5.Primary Key
A primary key is the unique identifier for each row of data.

1.1.6.SQL
SQL (Structured Query Language) is a standard programming language specifically designed for managing and manipulating relational databases. It provides a set of commands and syntax for performing various operations on data stored in a relational database management system (RDBMS).

1.1.7.Query
A query is a request for information from a database. It is a command or statement written in a query language. Queries can be used to retrieve specific records from one or more tables, update existing data, delete records, or perform calculations and data analysis.

1.1.8.Index
An index is a data structure used to optimize the retrieval of records from a database table. It acts like a lookup table that allows the database management system to quickly locate records based on the values of one or more columns.


1.1.9.Normalization
Normalization is the process of organizing and structuring the data in a database to reduce redundancy and dependency, improve data integrity, and minimize anomalies during data manipulation.

1.1.10.Database Management System (DBMS)
A database management system (DBMS) is a software system that enables users to define, create, maintain, and control access to databases. It provides an interface for users and applications to interact with databases, storing, retrieving, updating, and managing data efficiently and securely.


2.Section B: Discussions

2.1.1.Describe the purpose of a primary key in a database table and provide an example.

The primary key in a database table serves several essential purposes, namely:
1. Uniquely Identifies Records.
2. Enforces Data Integrity.
3. Facilitates Data Retrieval and Joins.
4. Supports Indexing.

Example to illustrate the purpose of a primary key:
In a database table named Students, information about students in a school is stored. Each student has a unique student ID assigned to them. By designating StudentID as the primary key, each student�s record in the Students Table can be uniquely identified by their student ID.



2.1.2.Explain the difference between a database management system (DBMS) and a database.

A database management system (DBMS) is software that facilitates the creation and management of databases, while a database is the actual repository or collection of structured data managed by the DBMS. The DBMS provides tools and functionalities for users to interact with the database, perform operations on the data, ensure data integrity and security, and optimize database performance.

2.1.3.Discuss in short, the importance of normalization in database design and provide an example of how it can improve data integrity.

Normalization is a crucial aspect of database design and its importance includes:
1. Reduction of Data Redundancy.
2. Prevention of Update Anomalies.
3. Facilitation of Data Integrity.
4. Simplified Database Maintenance.

Example illustrating how normalization improves data integrity:

Imagine a database table named Employees that stores information about employees, including their Departments and DepartmentLocation.
The department information is duplicated for each employee. If the location of the HR department changes, it must be updated for every employee in the HR department, increasing the risk of inconsistencies.
By normalizing the database, the Employees table references the Departments table using a foreign key (DepartmentID). This eliminates redundancy and ensures that department information is stored in only one place, thereby improving data integrity and reducing the risk of update anomalies.

