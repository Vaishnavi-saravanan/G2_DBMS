# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
create table student (rollno numeric ,name varchar(50) , age numeric
,address varchar(50) , phoneno varchar (10) );
 insert into student (rollno, name, age, address, phoneno) values (1,     -> 'manoj',23, 'dindugal','7889456235'),(2, 'vaishu', 21, 'chennai', '8567890123'),(3, 'jayabharathi', 19, 'kallakurichi', '9890123456');

### OUTPUT:
![Screenshot 2023-10-19 103208](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/7be7eb41-ef45-4d60-b188-e86584163994)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
 alter table student add department varchar(255);
### OUTPUT:
![Screenshot 2023-10-19 103514](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/e06e7a2e-1f43-4dc3-bcfd-9590434c3d3e)



### 3) Drop the student table
 
### SQL QUERY: 
 DROP TABLE student;
### OUTPUT:
![Screenshot 2023-10-19 103651](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/e48d80a3-a8b6-43d9-9924-5d81c107d94b)




### 4) Delete the student table using truncate keyword

### SQL QUERY: 
 TRUNCATE TABLE student;
### OUTPUT:
![Screenshot 2023-10-19 103838](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/94f7710e-04a3-4301-8f12-527d34c964dd)




### 5) Rename the student table to mystudent
### SQL QUERY: 
 CREATE TABLE mystudent AS SELECT * FROM student;

### OUTPUT:

![Screenshot 2023-10-19 104025](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/efa5c6d6-2058-4756-91f1-13c8fa500c84)
### RESULT:
The table is created successfully and queries are executed
