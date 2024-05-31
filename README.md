# Expense Tracker

Expense Tracker is a Python program designed to help you manage your expenses efficiently. It keeps a record of your expenses and assists in analyzing all expenditures accurately. The project is built using the Tkinter module for the graphical user interface and SQLite3 for the database.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)

## Introduction

Managing expenses is a crucial part of financial planning. The Expense Tracker application simplifies this process by providing an easy-to-use interface for recording and categorizing expenses. Whether you want to track daily expenses or analyze your spending habits over time, this tool offers a comprehensive solution. With categorized entries and essential functionalities like insertion, selection, deletion, and clearing of records, the Expense Tracker helps you stay on top of your finances.

## Features

- **Categorized Expenses**: Divide expenses into five categories for better organization.
- **CRUD Operations**: Perform Create, Read, Update, and Delete operations on your expense records.
- **Tkinter GUI**: User-friendly interface built with Tkinter, featuring Toplevel widgets for category-specific windows.
- **SQLite3 Database**: Reliable and efficient database management using SQLite3.

## Installation

To run this application, you need to have Python installed on your system. Additionally, you need to install several Python libraries.

1. **Install Python**: Download and install Python from [python.org](https://www.python.org/).

2. **Install Required Libraries**:
   Before using the program, you need to install the following libraries using `pip`. Open a terminal or command prompt and run the following commands:
   ```bash
   pip install tkinter
   pip install tkinter.ttk
   pip install db
   pip install sqlite3
   pip install datetime

## Usage

1. **Run the Application**:
   - Save the provided code in a file, for example, `expense_tracker.py`.
   - Open a terminal or command prompt and navigate to the directory where the file is saved.
   - Run the application using Python:
     ```bash
     python expense_tracker.py
     ```

2. **Manage Expenses**:
   - A main GUI window will open with options to choose one of the five expense categories or to exit.
   - **Select a Category**:
     - Click on the desired category button to open a new window specific to that category.
     - In the category window, you can perform the following actions:
       - **Insert**: Add a new expense record.
       - **Select All**: View all expense records in the category.
       - **Delete**: Remove a selected expense record.
       - **Clear**: Clear all records in the category.
       - **Exit**: Close the category window and return to the main menu.

## Example

1. **Run the Application**:
   - Open a terminal or command prompt and navigate to the directory where `expense_tracker.py` is saved.
   - Run the application using Python:
     ```bash
     python expense_tracker.py
     ```

## Contributors
| Sr No. | Name               |  git-profile     | 
| -------| -------------------| -----------------| 
| 1.     | Saniya Sonawane    |  saniyass0123    | 
