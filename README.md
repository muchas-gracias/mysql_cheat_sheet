<div style="background-color:#green; color:white; text-align:center; padding:50px;">

<img src="logo.png" alt="Logo" style="width:150px; 
margin-bottom:20px;">

# MySQL Cheatsheet

</div>

        


| Plugin                   |              README |
| ------------------------ | ------------------- |
| create new user          |       CREATE USER   |'username'@'localhost' IDENTIFIED BY 'password'; |
| grant privileges for new user | GRANT ALL PRIVILEGES ON *.* TO 'username'@'localhost';|
| apply privileges | FLUSH PRIVILEGES; |
|  |  |
| create database if one doesn't exist with certain name | CREATE DATABASE IF NOT EXISTS db_name;  |
| show all databases| SHOW DATABASES;  |
| show all tables| SHOW TABLES; |
| create table if one doesn't exist| CREATE TABLE [IF NOT EXISTS] table_name (Column_name1 datatype, Column_name2 datatype……); |
| insert values into the table| INSERT INTO table_name VALUES (value1, value2, value3, …);|
| add a column in the table| ALTER TABLE table ADD column_name datatype; |
| remove a column from the table| ALTER TABLE table_name
DROP column_name; |
| show all columns in the table| DESCRIBE table_name;  |
| modify a value in a column| UPDATE table_name SET column_name = 52000 WHERE column_name = 'John Smith'; |
| modify all values in a column| UPDATE table_name SET column_name = new_value; |
| delete an entire row| DELETE FROM table_name WHERE condition; |
| remove all rows from the table| DELETE FROM table_name;
 |
| remove all rows from table| TRUNCATE TABLE table_name;
 |
| find all values where a certain condition is met| SELECT * FROM table_name WHERE column_name = 2;
 |
| Use the database| USE db_name; |
| Use the database| USE db_name; |
| Use the database| USE db_name; |
| Use the database| USE db_name; |

