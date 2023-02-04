# KBA_Internship
project application

## Description

This is a simple Python program that implements the ability to receive input from the user, save the input to a database, and retrieve and display saved data. It uses SQLite, a lightweight database that can be easily embedded in a Python application, to store and retrieve the data.

## Development Tools & Prerequisites
To run this program, you will need the following:

1. Python 3 installed on your computer
2. SQLite3 library for Python
3. Instructions for executing the application
4. To run this program, follow these steps:
5. Open a terminal or command prompt.
6. Change the directory where the program is located.
7. Run the following command:
	" python database_application.py "
8. Follow the prompts in the program to enter a value.
9. The program will then save the value to the database and retrieve and display all saved data.


## Execution Flow
Here's an overview of how the program works:

1. The program connects to or creates a database file named "database.db".
2. It creates a table named "data" with a single column named "value".
3. The program receives input from the user using the input function.
4. The user input is inserted into the "data" table in the database.
5. The program retrieves and displays all saved data from the "data" table.
6. The database connection is closed when the program is finished.
