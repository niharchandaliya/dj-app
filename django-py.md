*Django*
========


## Basic requests

Creating a new project  

    $ django-admin startproject mysite

## Running Dev server
    $ python manage.py runserver [Optional port]

## Applying changing to db and py files
    $ python manage.py  migrate

### Views
* They take in requests and give back appropriate responses.

#### Common Usage 

    from django.urls import path
* They live in mysite/apps/views.py
* These are linked with urls.py in mysite/ path.

