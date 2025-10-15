# Employee Management System

## Overview
The Employee Management System is a desktop application designed to streamline employee data management for small businesses and organizations. Built with Python, it features a user-friendly graphical interface using Tkinter and supports image handling via the Pillow library. The system allows users to add, update, delete, and view employee records, including profile images, and integrates with a MySQL database for secure data storage and retrieval.
This project is a Python application that utilizes PIL (Pillow) and Tkinter for image processing and GUI functionality.

## Getting Started

### Clone the Repository
```bash
git clone https://github.com/jha-sourav/employee_management_system.git
cd "employee_management_system"
```

### Install Python
Ensure Python is installed. Download from [python.org](https://www.python.org/downloads/).

### Install Dependencies

#### Using pip:
```bash
pip install pillow
```

#### Using mysql-connector-python:
pip install mysql-connector-python

#### Using tkcalendar:
pip install tkcalendar

Tkinter is included with most Python installations. If not, install it:

- **Windows:** Usually included.
- **Linux (Debian/Ubuntu):**
    ```bash
    sudo apt-get install python3-tk
    ```
- **macOS:** Included with Python.

### Database Setup

1. Open **XAMPP** and start the **MySQL** service.
2. Import the provided database file into MySQL using phpMyAdmin or the MySQL command line.
    - In phpMyAdmin: Go to "Import" and select the `python_project_1.sql` file from the project in db folder.
    - If creating any db with different name then change the credentials in **database.py**

## Usage
To run the main Python script for employee by going to employee folder using:
```bash
cd employee
```
Then run:
```bash
python employeelogin.py
```

To run the main Python script for admin by going to admin/adminfiles folder using:
```bash
cd admin/adminfiles
```
Then run:
```bash
python adminlogin.py
```