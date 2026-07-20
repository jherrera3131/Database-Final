# COM303-Final
This repository contains the database systems final project completed by Miles and me.

Usage Instructions

Import the database files from the Dump20250509 folder into MySQL.

Copy .env.example to a new file named .env, then enter your local MySQL connection information:

DB_HOST=127.0.0.1
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_NAME=homedepot

Install the required packages:

python -m pip install mysql-connector-python python-dotenv

Run the interface with:

python db_final_demo.py
Interface Usage

The main menu contains options for the Database Administrator, Warehouse Manager, and Customer.

Enter the number associated with a user role to access the functions available to that user.