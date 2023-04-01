A relational database (RDB) is a way of structuring information in tables, rows, and columns. An RDB has the ability to establish links—or relationships–between information by joining tables, which makes it easy to understand and gain insights about the relationship between various data points. 

Developed by E.F. Codd from IBM in the 1970s, the relational database model allows any table to be related to another table using a common attribute. Instead of using hierarchical structures to organize data, Codd proposed a shift to using a data model where data is stored, accessed, and related in tables without reorganizing the tables that contain them. 

Think of the relational database as a collection of spreadsheet files that help businesses organize, manage, and relate data. In the relational database model, each “spreadsheet” is a table that stores information, represented as columns (attributes) and rows (records or tuples). 

Attributes (columns) specify a data type, and each record (or row) contains the value of that specific data type. All tables in a relational database have an attribute known as the primary key, which is a unique identifier of a row, and each row can be used to create a relationship between different tables using a foreign key—a reference to a primary key of another existing table.

Some of the most well-known RDBMSs include MySQL, PostgreSQL, MariaDB, Microsoft SQL Server, and Oracle Database

>> Benefits of relational databases <<
The main benefit of the relational database model is that it provides an intuitive way to represent data and allows easy access to related data points. As a result, relational databases are most commonly used by organizations that need to manage large amounts of structured data, from tracking inventory to processing transactional data to application logging. 

There are many other advantages to using relational databases to manage and store your data, including: 

Flexibility
It’s easy to add, update, or delete tables, relationships, and make other changes to data whenever you need without changing the overall database structure or impacting existing applications.

ACID compliance
Relational databases support ACID (Atomicity, Consistency, Isolation, Durability) performance to ensure data validity regardless of errors, failures, or other potential mishaps.

Ease of use
It’s easy to run complex queries using SQL, which enables even non-technical users to learn how to interact with the database.

Collaboration
Multiple people can operate and access data simultaneously. Built-in locking prevents simultaneous access to data when it’s being updated. 

Built-in security
Role-based security ensures data access is limited to specific users.

Database normalization
Relational databases employ a design technique known as normalization that reduces data redundancy and improves data integrity. 

![img](img/sql_tutorial.jpg)