# Django_API
How to use API for Django
Initialization --> in terminal:
1. conda create -n Django_API python=3.10

2. conda activate Django_API

3. conda install django

4. django-admin startproject config .
    4.1 python manage.py runserver --> to run our website --> for checking

5. python manage.py startapp store

6. python manage.py migrate --> the default migrations that allow us to create superuser

7. python manage.py createsuperuser --> create a superuser that have access to the admin panel