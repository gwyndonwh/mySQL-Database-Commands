# MySQL-Database-Commands
a comprehensive cheat sheet of mysql database commands

### How to login into mysql from terminal
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*

<br><br>

### How to SHOW USERS
		→ SELECT * FROM mysql.user;
*returns all the current mysql users*	

<br><br>

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

<br><br>

### How to SHOW PRIVILEGES
		→ SHOW GRANTS;
*shows the granted privileges for the current user*   

		→ SHOW GRANTS for 'user'@'localhost';
*shows the granted privileges for target user (the quotes are necessary)*  
*user = target username*  

<br><br>

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

<br><br>

### How to SHOW DATABASES
		→ SHOW DATABASES;
*shows all current databases in mysql*

<br><br>

### How to SELECT DATABASES
		→ USE database_name;
*sets your active database to the database titled database_name*

<br><br>

### How to DELETE DATABASES
		→ DROP DATABASE database_name;
*deletes the database titled database_name*

<br><br>

### How to CREATE a TABLE with Columns and their data types
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*

<br><br>

### How to SHOW, DELETE & DROP Tables

<br><br>

### How to Insert ROWS & RECORDS (single and multiple)

<br><br>

### How to SELECT with the WHERE Clause

<br><br>

How to SELECT with the WHERE Clause using a range
How to DELETE an individual ROW
How to UPDATE a ROW
How to add a new column and modify it
How to Order by and use Distinct
How to Concatenate Columns
How to Select Distinct Rows
How to use LIKE to Search
How Select using IN
How to Create & Remove Index
How to Create a New Table with Foreign Key (Posts)
How to use Inner Join
How to JOIN Multiple Tables

