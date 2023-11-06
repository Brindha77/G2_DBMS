# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE : 4.8.23
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student(rollno numeric(10),name char(10),age numeric(5),address varchar(25),phoneno numeric(15));

### OUTPUT:
![image](https://github.com/Brindha77/G2_DBMS/assets/118889143/728693e2-c052-41fa-bb2c-8e35b1a382c5)

### QUERY: 
Change the above student table by adding another attribute department
### SQL QUERY:
alter table student add department varchar(15);

### OUTPUT:
![image](https://github.com/Brindha77/G2_DBMS/assets/118889143/47f028ed-8cd4-450b-8b59-d234b317e39d)

### QUERY: 
Drop the student table
 
### SQL QUERY: 
drop table student;
### OUTPUT:
![image](https://github.com/Brindha77/G2_DBMS/assets/118889143/8032f4f9-c068-4eae-93c1-da89db122e78)

### QUERY:
Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:
![image](https://github.com/Brindha77/G2_DBMS/assets/118889143/1e56affd-8ec9-43e6-80af-94f52b2d0c17)

### QUERY:
Rename the student table to mystudent

### SQL QUERY: 
rename table student to mystudent;

### OUTPUT:
![image](https://github.com/Brindha77/G2_DBMS/assets/118889143/0bd7e2ef-7238-45a4-81ea-13d6dda24a8a)
## RESULT :
The queries got the output and statifies the given question.
