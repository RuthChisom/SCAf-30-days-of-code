# SCA-30-days-of-code
 Setting up a new Django Project

Day 1

1. Create a new Django project. (install python if not already on your system)
    - python -m venv venv
    - source venv/Scripts/activate
    - pip install django
    - django-admin startproject core .
2. Create 5 apps with the names; users, profiles, payment, comment and blog.
    - python manage.py startapp users
    - python manage.py startapp profiles  ....and so on
3. Connect the apps to your core project settings.
- add 'users.apps.UsersConfig' in core/settings.py   ....and so on
4. Run your server.
    - python manage.py runserver
