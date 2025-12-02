# Student Management System

A simple **Python Tkinter application** for managing student records, along with a **SQL Server connection** using `pyodbc`.

---

## Features
- Add, view, update, and delete students  
- Simple Tkinter GUI  
- Connects to SQL Server using ODBC Driver 18  
- Automatically creates the `students` table if it doesn't exist  

---

## Requirements
- Python 3  
- `pyodbc`  
- SQL Server Express  
- ODBC Driver 18  

Install dependency:
```bash
pip install pyodbc
```

---

## How to Run
python main.py

Use your correct SQL Server instance name, for example:

`DESKTOP-M2HN7DT\SQLEXPRESS`

---

## Description

On startup, the program connects to SQL Server and ensures the students table exists.
The Tkinter GUI allows basic CRUD operations on a student list stored in Python.

