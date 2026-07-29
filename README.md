# Banking System — A Secure Online Banking Management Platform

A web-based banking management system built using Python and Django that provides
basic banking operations such as account management, transactions, user authentication,
and administrative control.

The application allows customers to create accounts, manage their profiles, perform
transactions, and securely track their banking activities through a simple and
user-friendly interface.

## Live Demo:-https://sankethd.pythonanywhere.com/
## Login Details
       User Name:-John@gmail.com
       Password:-John@1234
# Tech Stack

| Layer | Technology |
|-------|------------|
| Backend | Python, Django |
| Frontend | HTML5, CSS3, JavaScript, Bootstrap |
| Database | SQLite |
| Authentication | Django Authentication System |
| API | Django REST Framework |
| Deployment | PythonAnywhere |
| Version Control | Git & GitHub |

# Installation & Setup
1. Clone Repository:-
git clone https://github.com/Sanketh0705/banking-system.git
cd banking-system
2. Create Virtual Environment:-
venv\Scripts\activate
3.Install Dependencies:-
pip install -r requirements.txt
4. Database Setup:-
python manage.py migrate
python manage.py createsuperuser
5. Run Development Server:-
python manage.py runserver
http://127.0.0.1:8000/

# Security Features

The project implements:
Django built-in authentication,
Password hashing,
CSRF protection,
Secure sessions,
Form validation,
User authorization.

# Deployment
The project is deployed using:PythonAnywhere

Deployment process:

Upload project to server,
Create virtual environment,
Install dependencies,
Configure WSGI application,
Configure static files,
Run migrations,
Reload web application.

# Testing

User authentication,
Account creation,
Transactions,
Database operations,
Admin functionality,
Deployment environment.

# Requirements:-

Django,
SQLite,
Pillow,
python-dateutil,
celery,
django-celery-beat.
