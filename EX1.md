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


### OUTPUT:
![Screenshot 2023-09-09 135236](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/5e1246d3-3c50-4b7a-9551-5c9b092a0ec0)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 

### OUTPUT:
![Screenshot 2023-09-09 140207](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/30ef0a7e-0d9b-4070-ad6f-4d369268e04a)


### 3) Drop the student table
 
### SQL QUERY: 


### OUTPUT:

![Screenshot 2023-09-09 140943](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/3997801a-9b17-46ce-9920-538f8688b04b)


### 4) Delete the student table using truncate keyword

### SQL QUERY: 


### OUTPUT:
![Screenshot 2023-09-09 141423](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/5616a28a-ce81-4064-9452-047fc629e538)



### 5) Rename the student table to mystudent

### SQL QUERY: 


### OUTPUT:
![Screenshot 2023-09-09 142111](https://github.com/Vaishnavi-saravanan/G2_DBMS/assets/118541897/98b7489c-cd43-4b52-b50e-624166e60c28)
