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
|  
| create database if one doesn't exist with certain name | CREATE DATABASE IF NOT EXISTS db_name;  |
| show all databases| SHOW DATABASES;  |
| show all tables| SHOW TABLES; |
| create table if one doesn't exist| CREATE TABLE [IF NOT EXISTS] table_name (Column_name1 datatype, Column_name2 datatype……); |
| insert values into the table| INSERT INTO table_name VALUES (value1, value2, value3, …);|
| add a column in the table| ALTER TABLE table ADD column_name datatype; |
| remove a column from the table| ALTER TABLE table_name|
| show all columns in the table| SHOW COLUMNS FROM table_name;  |
| modify a value in a column| UPDATE table_name SET column_name = 52000 WHERE column_name = 'John Smith'; |
| modify all values in a column| UPDATE table_name SET column_name = new_value; |
| delete an entire row| DELETE FROM table_name WHERE condition; |
| remove all rows from the table| DELETE FROM table_name;
 |
| remove all rows from table| TRUNCATE TABLE table_name;
 |
| find all values where a certain condition is met| SELECT * FROM table_name WHERE column_name = 2;
 |
| sort by column ascending| SELECT * FROM table_name ORDER BY column_name ASC; |
| sort by column descending| SELECT * FROM table_name ORDER BY column_name DESC; |
| select all from parameters but limit | SELECT * FROM table_name LIMIT 10  |
| count rows| SELECT COUNT(*) FROM table_name;
 |
| find max and min| SELECT MAX(column_name), MIN(column_name) FROM table_name;
 |
| find average| SELECT AVG(column_name) FROM table_name; |
|
| find sum | SELECT SUM(column_name) FROM table_name;
| show current database| SELECT DATABASE();
| show active connections to database| SHOW PROCESSLIST;
|
| backup database to file| mysqldump -u username -p database_name > backup.sql
 | import data| mysql -u username -p database_name < backup.sql;  |
 | commit changes| COMMIT;
 | rollback changes| ROLLBACK;
 | start a transaction| START TRANSACTION;
 | rename a table| RENAME TABLE old_table_name TO new_table_name;


