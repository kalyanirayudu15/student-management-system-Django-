# Student Management System

A simple **Student Management System** developed using **Python Django** and **SQLite**. The application allows users to manage student information through a web-based interface.

## Features

* View all student records
* Add new student details
* View individual student details
* Edit existing student information
* Delete student records
* Store student information using SQLite database
* Django class-based views for CRUD operations

## Student Information

The system stores the following details:

* Name
* Identity Number
* Address
* Department
* Email
* Aadhaar Number
* Blood Group

## Technologies Used

* **Python**
* **Django**
* **SQLite**
* **HTML**
* **Django Templates**

## Project Structure

```text
student-management-system/
│
├── manage.py
├── db.sqlite3
│
├── rattlesnake/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
└── rattles/
    ├── models.py
    ├── views.py
    ├── urls.py
    ├── admin.py
    ├── migrations/
    └── templates/
        └── rattles/
            ├── student_list.html
            ├── student_form.html
            ├── student_detail.html
            └── student_confirm_delete.html
```

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/kalyanirayudu15/student-management-system-Django-.git
```

### 2. Navigate to the project folder

```bash
cd student-management-system-Django-
```

### 3. Install Django

```bash
pip install django
```

### 4. Apply migrations

```bash
python manage.py migrate
```

### 5. Run the development server

```bash
python manage.py runserver
```

### 6. Open the application

Open the URL shown in the terminal, usually:

```text
http://127.0.0.1:8000/
```

The student management application is available under:

```text
http://127.0.0.1:8000/rattles/
```

## CRUD Operations

The application implements the main CRUD operations:

| Operation | Description                      |
| --------- | -------------------------------- |
| Create    | Add a new student                |
| Read      | View student records and details |
| Update    | Edit student information         |
| Delete    | Remove a student record          |

## Purpose

This project was developed as a learning project to understand **Django web development, models, views, templates, URL routing, database integration, and CRUD operations**.

## Author

**Kalyani Rayudu**
