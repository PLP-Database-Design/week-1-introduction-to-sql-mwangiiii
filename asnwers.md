# SQL Assignment Week 1

## State and Explain the components of a DBMS(Database Management System)
1. database - collection of organized data typically stored in rows and columns which the DBMS manages. 

2. DBMS software - software responsible for managing the database. it provides the UI that is responsible to manage the database.

3. Quesry processor - converts high level queries for SQL into low level instructions for data retrieval.

4. Database engine -  is the core service that performs operations like data storage, retrieval and updates. Handles tasks such as transaction processing, concurrency and data consistency. 

5. Data dictionary - stores information about the database structure such as columns, data types constraints and relationships.

## What is a relational database? Give 4 examples.
A relational database is a collection of related data that is stored in the structure of rows and columns. 
### examples include: 
1. SQL
2. PostgreSQL
3. Oracle database
4. Microsoft SQL server

## State and Explain three classifications of SQL?
1. Data Definition Language (DDL)
> defines and manages the structure of the database and its objects e.g. tables, indexs and constraints. e.g. create, alter, drop, truncate

2. Data Manipulation Language (DML)
> handles the manipulation of data stored in the database. e.g. Select, insert, update, delete.

3. Data control Language (DCL)
> controls the access to the database by managing permissions and security. e.g. GRANT, REVOKE

4. Data Query Language (DQL)
> focuses on retrieving data from the database

## What is the difference between a Primary Key and a Foreign Key?
Primary key is a column used to uniquely reference each row in a table while a foreign key is used to column that is used to establish a relationship between this table and another table by referencing to the primary key of the referenced table.

## What is an Entity-Relationship Diagram?
> graphical representation of the relationships between entities in a database and is used during the database design process to visually model the data, define the structure of the database and illustrate how different entities interact with each other.

## What are the advantages of relational databases?
1) Data integrity through use of Primary and foreign keys.
2) Flexibility with querying 
3) can handle large volumes of data
4) data is stored in tables with clear relationships and this makes it easier to model real world data.
5) Robust access control measures ensure data is accessed to authorised specified users

## State four types of data type used to store data in tables?
- int - numeric data type
- varchar -  string data type
- date - date and time
- Boolean 

## What is the purpose of a database management system (DBMS)?
> it is used to create and manage databases