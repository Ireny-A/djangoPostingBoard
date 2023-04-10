# Django Posting Board
This is a simple web application built with Django that allows users to create an account, post, and view listings. The application also allows users to edit or delete their posts.

## Features
User registration and authentication
Create, update, delete listings
Browse and search listings
## Installation
Clone the repository
Create a database by running python manage.py migrate, python manage.py makemigrations
Start the development server by running python manage.py runserver
## Deployment
To deploy this application to a live server, you need to follow these steps:

Set DEBUG = False in settings.py
Add ALLOWED_HOSTS to the list of allowed hosts (e.g., ALLOWED_HOSTS = ['example.com'])
Set up your database and create database tables
Run the application with a production WSGI server (e.g., Gunicorn)
Contributing
Contributions to this project are welcome! If you find any bugs or have suggestions for new features please feel free to open an issue or submit a pull request.

### Credits
This project was created by Irina Anishchenko.
