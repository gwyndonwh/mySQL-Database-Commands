# MySQL-Database-Commands
a comprehensive cheat sheet of mysql database commands

### How to login into mysql from terminal
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*

		
### How to SHOW USERS
		→ SELECT * FROM mysql.user;
*returns all the current mysql users*		


### How to CREATE USERS
		→ CREATE USER username IDENTIFIED BY password;
*creates a new blank user*
*username = new username*
*password = new user's password*


### How to GRANT PRIVILEGES, Show granted privileges and remove.
		→ GRANT privilege
		  ON object
		  TO target
		  [WITH GRANT OPTION];
*grant a privilege for a part of the sql to a user or group*

*privilege = the privilege you wish to grant*

*object	  = the sql object youre granting permission for (database, table, etc)*

*target	  = who youre granting the privilege to (single user, all users with a role, etc)*

*[WITH GRANT OPTION] allows the user to grant privileges to other users*


### How to SHOW, DELETE & CREATE DATABASES & SELECT DATABASES
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*


### How to CREATE a TABLE with Columns and their data types
		→ mysql -u root -p
*-u refers to the user (root) and -p refers to the password (entered after)*


How to SHOW, DELETE & DROP Tables


How to Insert ROWS & RECORDS (single and multiple)


How to SELECT with the WHERE Clause


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

