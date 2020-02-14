# MySQL-Database-Commands
a comprehensive cheat sheet of mysql database commands

### How to login into mysql from terminal
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*

<br><br>

### How to SHOW USERS
		→ SELECT * FROM mysql.user;
*returns all the current mysql users*	

<br>

### How to CREATE USERS
		→ CREATE USER username IDENTIFIED BY password;
*creates a new blank user*  
*username = new username*  
*password = new user's password*

<br><br>

### How to GRANT PRIVILEGES
		→ GRANT privilege
		  ON object
		  TO target
		  [WITH GRANT OPTION];
*grant a privilege for a part of the sql to a user or group*  
*privilege = the privilege you wish to grant*  
*object	   = the sql object youre granting permission for (database, table, etc)*  
*target	   = who youre granting the privilege to (single user, all users with a role, etc)*  
*[WITH GRANT OPTION] allows the user to grant privileges to other users*  

<br>

### How to SHOW PRIVILEGES
		→ SHOW GRANTS;
*shows the granted privileges for the current user*   

		→ SHOW GRANTS for 'user'@'localhost';
*shows the granted privileges for target user*  
*user = target username*  

<br>

### How to REMOVE PRIVILEGES
		→ REVOKE privilege
		  ON object
		  FROM target;
*remove a privilege for a part of the sql from a user or group*  
*privilege = the privilege you wish to grant*  
*object	   = the sql object youre granting permission for (database, table, etc)*  
*target	   = who youre granting the privilege to (single user, all users with a role, etc)*   

<br><br>

### How to CREATE DATABASES
		→ CREATE DATABASE database_name;
*creates a new database titled database_name*

<br>

### How to SHOW DATABASES
		→ SHOW DATABASES;
*shows all current databases in mysql*

<br>

### How to SELECT DATABASES
		→ USE database_name;
*sets your active database to the database titled database_name*

<br>

### How to DELETE DATABASES
		→ DROP DATABASE database_name;
*deletes the database titled database_name*

<br><br>

### How to CREATE a TABLE with Columns and their data types
		→ CREATE TABLE table_name ( 
		  column_one INT PRIMARY KEY AUTO_INCREMENT NOT NULL, 
		  column_two VARCHAR(20) NOT NULL, 
		  column_three SMALLINT NOT NULL 
		  ); 
*creates a table with three columns, replace the values following column_x with your desired datatypes*  
*table_name = new table name*  
*column_x = new column name*  

<br><br>

### How to SHOW Tables
		→ SHOW TABLES;
*shows all the tables in the selected database*  

<br><br>

### How to DESCRIBE Tables
		→ DESCRIBE table_name;
*shows the column structure of the described table*  

<br><br>

### How to DELETE Tables
		→ DROP TABLE table_name;
*deletes the table from the database along with the data inside*

<br><br>

### How to Insert RECORD (single)
		→ INSERT INTO table_name (column1, column2, column3)
		  VALUES ('value1', 'value2', 'value3');
*inserts a single row of values into target columns in table_name*

<br><br>

### How to Insert RECORDS (multiple)
		→ INSERT INTO table_name (column1, column2, column3)
		  VALUES ('value1', 'value2', 'value3'),
		  	 ('value1', 'value2', 'value3'),
			 ('value1', 'value2', 'value3');
*inserts a three rows of values into target columns in table_name*

<br><br>

### How to SELECT with the WHERE Clause
		→ SELECT * FROM table_name WHERE column1 = 'value1';
*displays the rows where column1 is equal to the value of value1*

<br><br>

### How to SELECT with the WHERE Clause using a range
		→ SELECT * FROM table_name WHERE column1 BETWEEN 10 AND 15;
*displays the rows where column1 is 10, 11, 12, 13, 14 or 15*

<br><br>

### How to DELETE an individual ROW
		→ DELETE FROM table_name WHERE column1 = 'value1';
*deletes the rows where column1 is equal to the value of value1*

<br><br>

### How to UPDATE a ROW

### How to add a new column and modify it

### How to Order by and use Distinct

### How to Concatenate Columns

### How to Select Distinct Rows

### How to use LIKE to Search

### How Select using IN

### How to Create & Remove Index

### How to Create a New Table with Foreign Key (Posts)

### How to use Inner Join

### How to JOIN Multiple Tables


