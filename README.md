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

create table student_table(Roll_no numeric(10) , Name varchar(20) , Age numeric(3), Address varchar(20) , Phone_no numeric(10));


### OUTPUT:
![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/4a32c0c9-ee02-4e11-a898-2abd9be28300)
![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/bc2e9eba-0b51-4790-aa3a-1626e6454cfb)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
 alter table student_table add Department varchar(20);

### OUTPUT:
![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/3646d875-ce27-4667-b5a4-b2540c578cbf)


### 3) Drop the student table
 
### SQL QUERY: 
drop table student_table;

### OUTPUT:
![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/fde9478b-5bfc-4f46-93da-8a8ad27a82e4)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student_table;

### OUTPUT:

![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/a76ab110-03a0-4ee0-8aac-c6c75e688ec0)


### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student_table rename to stud;

### OUTPUT:
![image](https://github.com/kavinesh8476/H2_DBMS/assets/118466561/bab1d99d-1b2f-4136-86f7-a14436069ec4)
### RESULT:
Thus , a student database is created and DDL queries are executed in SQL.

