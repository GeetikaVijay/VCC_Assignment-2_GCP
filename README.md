# VCC_Assignment-2_GCP
Google Cloud Virtual Machines

# Author

	-- Roll No 			: G23AI2098
	-- Student Name 	: Geetika Vijay
 
# Web Application details 

	--	This is a Stream Lit App to Query Mysql Database
	--  A simple UI app created to dynamically query data from MySql database hosted on any VM

# Features

	-- List Tables
	-- Dynamic Querying

# Software Requirements

	-- Python 3.10 or later
	-- Database Server ( Mysql )

# My Sql Deploy Script 

	-- Update the package index >> sudo apt-get update
	-- Install MySQL Server >> sudo apt-get install -y mysql-server
	-- Start the MySQL service >> sudo systemctl start mysql
	-- Enable MySQL to start on boot >> sudo systemctl enable mysql
	-- Run the mysql_secure_installation script to secure your MySQL installation >> sudo mysql_secure_installation
	-- Create a test database and user >> CREATE DATABASE EMPLOYEES;
	-- Create a table in the database and insert some dummy values into it.
		
		CREATE TABLE employees 	(
									employee_id VARCHAR(50) PRIMARY KEY,
									employee_name VARCHAR(100) NOT NULL,
									employee_company VARCHAR(100) NOT NULL,
									employee_email VARCHAR(100) NOT NULL
								) ;
								
	-- You can create the DB_NAME, DB_USER, DB_PASS, and TABLE_NAME variables as needed.

# Access webserver from host machine and insert data database installed on virtual machine 2.
# Access iserted records successfully in virtual machine 2. 
