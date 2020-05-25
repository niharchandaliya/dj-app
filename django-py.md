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
* To add a view add the path of view file to mysite/app/urls.py
* And also to mysite/urls.py


### Urls
* In url files specifically in app/urls.py use the import as follows

    from . import views
The `.` specifies importing from the same path as the urls.py.