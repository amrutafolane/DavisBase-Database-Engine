# DavisBase-Database-Engine
Database engine from scratch

•	This project builds an entire database engine right from scratch including all the implementations like file-structures using B-trees, all the basic commands like SELECT, CREATE TABLE, etc.
•	Implemented the system backend in JAVA, using JsqlParser for parsing the user input commands

Execution Instructions:
In command prompt/terminal run below command:
Java -jar mydatabase.jar
It will start the application in command prompt and will create a data directory in same path
where .jar file is kept.
Path to source code: \DavisBase\src\com\myDatabase
Supported Commands
1. CREATE TABLE table_name (column_name1 int primary key,
Column_name2 data_type2 [not null],
…..);
First column should be integer and primary key.
2. SHOW TABLES;
3. DROP TABLE table_name;
4. INSERT INTO table_name (column_name1, column_name2…) values (value1,
value2….);
Does not support space in text data, use underscore (_) instead of space in text data.
5. SELECT-FROM-WHERE
supports only single column in where clause, greater than/less than comparison
implemented for numeric data types.
6. DELETE FROM table_name WHERE column1 operator value1
If where condition not provided, all records from the table are deleted, greater than/less
than comparison implemented for numeric data types
7. UPDATE table_name SET column1 = value1 WHERE column2 operator value 2
If where condition not provided, all records from the table are updated, greater than/less
than comparison implemented for numeric data types
8. Help;
9. Exit;
