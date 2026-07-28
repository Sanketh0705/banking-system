# Banking System — A Secure Online Banking Management Platform

A web-based banking management system built using Python and Django that provides
basic banking operations such as account management, transactions, user authentication,
and administrative control.

The application allows customers to create accounts, manage their profiles, perform
transactions, and securely track their banking activities through a simple and
user-friendly interface.

## Live Demo:-https://sankethd.pythonanywhere.com/

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

# Project Structure

banking-system/

├── accounts/
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── templates/
│
├── transactions/
│ ├── models.py
│ ├── views.py
│ └── urls.py
│
├── banking_system/
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
│
├── static/
│ ├── css/
│ ├── js/
│ └── images/
│
├── templates/
│
├── manage.py
├── requirements.txt
└── README.md


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


# Requirements:-
Django
SQLite
Pillow
python-dateutil
celery
django-celery-beat
