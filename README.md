# BookStore Backend
This project is the backend of a Online Bookstore. It uses Django(Django Rest Framework) and Postgres SQL for database management. The application includes RESTful APIs for Books(Add Book,Delete Book,Update Book,Retrieve Book) and user registration and authorization. The application is hosted on AWS EC2 for deployment.

# Prerequisites
Python 3.12 or higher \
PostgreSQL 16.1 or higher \
Django 4.2.7 or higher \
DjangoRestFramework 3.14 or higher \
  ## Install Dependencies
     pip install Django
     pip install djangorestframework
     pip install Markdown
     pip install django-filter
     pip install pillow
     pip install django-cors-headers
     pip install psycopg2

## Usage Instructions
Clone this repository e.g.

```
git clone https://github.com/in-coder-aps/BookStoreBackend.git
```  

Run migrations to update/create database
```
python manage.py makemigrations
python manage.py migrate
```

Run the Django development server
```
python manage.py runserver
```

Navigate to to http://127.0.0.1:8000
