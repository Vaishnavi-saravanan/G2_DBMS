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
 ```
create table student (rollno numeric ,name varchar(50) , age numeric
,address varchar(50) , phoneno varchar (10) );
insert into student (rollno, name, age, address, phoneno) values (1,     -> 'manoj',23, 'dindugal','7889456235'),(2, 'vaishu', 21, 'chennai', '8567890123'),(3, 'jayabharathi', 19, 'kallakurichi', '9890123456');
```
### OUTPUT:
![Screenshot 2023-10-19 103208](https://github.com/dineshgl/G2_DBMS/assets/118541897/9bcbddc4-57ab-4cbe-b7cb-01a2f4106bd5)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
CREATE TABLE mystudent AS SELECT * FROM student;
```
### OUTPUT:
![Screenshot 2023-10-19 103514](https://github.com/dineshgl/G2_DBMS/assets/118541897/e4b0754a-36e7-478f-8bc6-acc7e7ba9ffe)


### 3) Drop the student table
 
### SQL QUERY: 
```
DROP TABLE student;
```
### OUTPUT:
![Screenshot 2023-10-19 103651](https://github.com/dineshgl/G2_DBMS/assets/118541897/8271d634-ed46-4b2e-84f7-474a15125535)

### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
 TRUNCATE TABLE student;
```

### OUTPUT:
![Screenshot 2023-10-19 103838](https://github.com/dineshgl/G2_DBMS/assets/118541897/39bf85c0-a26b-46e0-9571-5ed8ab6a9586)

### 5) Rename the student table to mystudent

### SQL QUERY: 
```
 CREATE TABLE mystudent AS SELECT * FROM student;
```
### OUTPUT:
![Screenshot 2023-10-19 104025](https://github.com/dineshgl/G2_DBMS/assets/118541897/55569603-3e17-4db0-ab6c-566185f39655)
### RESULT :
The queries got the output and statifies the given question.
