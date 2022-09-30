# SCA-30-days-of-code
<<<<<<< HEAD
=======
 Setting up a new Django Project
>>>>>>> 89030f9b6b2524ec98dbd4c828eb63577297b8c0
Day 1 - Setting up a new Django Project

1. Create a new Django project. (install python if not already on your system)
    - python -m venv venv
    - source venv/Scripts/activate
    - pip install django
    - django-admin startproject core . //the dot stops it from creating double core folders
2. Create 5 apps with the names; users, profiles, payment, comment and blog.
    - python manage.py startapp users
    - python manage.py startapp profiles  ....and so on
3. Connect the apps to your core project settings.
    - add 'users.apps.UsersConfig' in core/settings.py, under INSTALLED_APPS   ....and so on
4.  Apply initial database migrations. This creates the tables for the applications listed in the INSTALLED_APPS setting in the database
    - python manage.py migrate
4. Run your server.
    - python manage.py runserver

Note: You can run the Django development server on a custom host and port or tell Django to load a specific settings file
    - python manage.py runserver 127.0.0.1:8001 --settings=mysite.settings
