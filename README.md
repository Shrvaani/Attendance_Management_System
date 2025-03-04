# Office Attendance Management System

## Overview
This is a simple attendance management system implemented using Python's Tkinter library and SQLite database. The system allows users to register, log in, and mark their attendance as present or absent. An admin page is also provided to view the attendance records of all users.
## Dependencies
The following dependencies are required to run the system:

## Dependencies
Ensure you have Python installed (version 3 or later). 

The required dependencies are:
1. Tkinter (built-in with Python 3)
2. SQLite3 (built-in with Python 3)

# Installation

No additional installation is required, as Tkinter and SQLite3 come pre-installed with Python. Simply clone the repository and navigate to the project folder.

# Usage
To run the system, execute the following command in the terminal:
```
python attendance.py
```
This will launch the GUI for the system. Users can then register, log in, and mark their attendance using the provided interface.

# Features:

The system consists of four main components:

1. Login Page - Allows users to log in using their registered username and password. If valid, they are directed to the attendance page.
2. Registration Page - Allows users to register a new account by providing a valid username and password. A success message is displayed upon registration.
3. Attendance Page - Displays the user's username and date, allowing them to mark their attendance as present or absent.
4. Admin Page - Allows admins to view the attendance records of all users.

The system uses an SQLite database to store user information and attendance records.
