# Office Employees Management System (OEMS)

## Introduction

Office Employees Management System (OEMS) is a comprehensive web application developed using the Django framework in Python. This project aims to manage employee data effectively, covering various aspects such as personal information, attendance, leave management, and more. It is designed to be a helpful resource for both freshers and experienced developers to enhance their skills and can be included in resumes.

## Features

- **View All Employees**: Display a list of all employees.
- **Add Employee**: Add new employee details.
- **Remove Employee**: Remove existing employees.
- **Filter Employee**: Filter employees based on specific criteria.

## Technologies Used

- Python
- Django Framework
- Django ORM
- Django Queryset
- Basic SQL
- HTML
- CSS
- Bootstrap

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.akshaykadam22/ofc-emp-management-system.git
   cd ofc-emp-management-system
Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Setup the database:

Update the database configuration in settings.py as per your setup.
Run the following commands to create database migrations and apply them:
bash
Copy code
python manage.py makemigrations
python manage.py migrate
Create a superuser:

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Usage
Access the application at http://127.0.0.1:8000/.
Log in to the admin interface at http://127.0.0.1:8000/admin using the superuser credentials.
Use the interface to add, view, remove, and filter employee details.
Project Structure
plaintext
Copy code
OEMS/
├── manage.py
├── OEMS/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
├── employees/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── templates/
│   │   ├── add_employee.html
│   │   ├── view_all_employees.html
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   ├── migrations/
