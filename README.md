# Description
This project is devoted to visually impaired people. The purpose is to create ultrasonic glasses with AI.

# Small tips
### Create a new project called backend:
django-admin startproject backend

### Start a new application called todo:
python manage.py startapp todo

### Run migrations:
python manage.py migrate

### Start up the server:
python manage.py runserver

### Create migration
python manage.py makemigrations todo

### Create a “superuser” account to access the admin interface
python manage.py createsuperuser

More details
https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react

# Technical description
A web service "webserv" consists of the frontend part (Reactjs) and backend part (Diango).
The camera of glasses captures an image and sends to a web service webserv. It responds with the name of object found
on the image.
