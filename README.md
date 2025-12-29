# sql-day1
1. Which SQL command is used to display all the databases in MySQL?

The SQL command is:

SHOW DATABASES;


This command lists all databases available in the MySQL server.

2. How do you get the details of datatypes in a table?

You can use the following command:

DESCRIBE table_name;


or

DESC table_name;


This command displays:

Column names

Data types

Size

Whether NULL values are allowed

Key information (Primary key, etc.)

Example:

DESCRIBE student;
