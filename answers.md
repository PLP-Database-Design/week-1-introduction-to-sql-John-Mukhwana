# Database Management Systems (DBMS) Assignment

### **1. State and Explain the Components of a DBMS**

A DBMS consists of the following components:

1. **Database Engine**  
   The core service for storing, processing, and securing data. It allows for data access, management, and manipulation.

2. **Database Schema**  
   Defines the structure of the database, including tables, fields, relationships, and constraints.

3. **Query Processor**  
   Interprets and executes SQL queries, optimizing performance and ensuring the correct data is retrieved or modified.

4. **Data Manager**  
   Manages the organization of data on physical storage devices.

5. **Transaction Manager**  
   Ensures data integrity by managing transactions (sequences of operations), providing features like atomicity and rollback in case of failures.

6. **Authorization and Security Manager**  
   Controls access to data, ensuring only authorized users can perform specific actions.

7. **Report and Analysis Tools**  
   Provides utilities for analyzing data and generating reports.

---

### **2. What is a Relational Database? Give 4 Examples**

A **relational database** organizes data into tables (relations) with rows and columns. Relationships between tables are defined using keys.

Examples:
- MySQL
- PostgreSQL
- Oracle Database
- Microsoft SQL Server

---

### **3. State and Explain Three Classifications of SQL**

1. **Data Definition Language (DDL)**  
   - Commands: `CREATE`, `ALTER`, `DROP`  
   - Used to define and manage database schema.

2. **Data Manipulation Language (DML)**  
   - Commands: `INSERT`, `UPDATE`, `DELETE`  
   - Focuses on manipulating data within tables.

3. **Data Query Language (DQL)**  
   - Command: `SELECT`  
   - Used to retrieve data from a database.

---

### **4. What is the Difference Between a Primary Key and a Foreign Key?**

| **Primary Key**                          | **Foreign Key**                              |
|------------------------------------------|----------------------------------------------|
| Uniquely identifies each record in a table. | Refers to the primary key in another table.  |
| Ensures no duplicate values in the column. | Helps establish relationships between tables. |
| Only one primary key per table is allowed. | A table can have multiple foreign keys.       |

---

### **5. What is an Entity-Relationship Diagram?**

An **Entity-Relationship Diagram (ERD)** is a visual representation of the entities in a database and their relationships. It uses symbols like:
- Rectangles for entities
- Diamonds for relationships
- Ovals for attributes

---

### **6. What are the Advantages of Relational Databases?**

1. **Data Integrity**: Ensures accuracy and consistency using constraints like primary keys.  
2. **Ease of Use**: Familiar tabular format makes it easy to understand and manage.  
3. **Flexibility**: Relationships between data are dynamic and scalable.  
4. **Standardized Query Language**: SQL is widely supported for querying.  
5. **Data Security**: Offers fine-grained control over access rights.

---

### **7. State Four Types of Data Types Used to Store Data in Tables**

1. **Integer (INT)**: Stores whole numbers.  
2. **Varchar (VARCHAR)**: Stores variable-length strings.  
3. **Date (DATE)**: Stores date values.  
4. **Float (FLOAT)**: Stores floating-point numbers (decimals).

---

### **8. What is the Purpose of a Database Management System (DBMS)?**

The purpose of a DBMS includes:

1. **Store, Organize, and Manage Data**: Provides efficient data management.  
2. **Enable Easy Data Retrieval**: Allows for complex queries using SQL.  
3. **Maintain Data Integrity and Security**: Protects data from unauthorized access or corruption.  
4. **Support Concurrent Users**: Enables multiple users to access and manipulate data simultaneously.  
5. **Backup and Recovery**: Ensures data recovery in case of failures.
