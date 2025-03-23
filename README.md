# COMP6006 Web Application Frameworks
COMP6006 Web Application Frameworks -  Assignment 1
Title: Developing a Secure Task Management Web Application using Django 

Django Project Setup and How to Run:

1. Ensure you have Python, Django and Django-admin installed
  python --version
  django --version
  django-admin --version

2. Created a Django project task_manager
   django-admin startproject task_manager
   
3. Created a Django app tasks_app

4. Run the server 
   python manage.py runserver

   After this you get the localhost link, which can use to check whether server is running 

6. For Migrations
   python manage.py makemigrations
   python manage.py migrate

Webpages in the project:

Home: http://127.0.0.1:8000/
Create task: http://127.0.0.1:8000/create/
Display All Task list: http://127.0.0.1:8000/alltasks/
Display Single task using URL parameters:http://127.0.0.1:8000/task/3/
Display All Categories: http://127.0.0.1:8000/allcategories/
Display Task under a category: http://127.0.0.1:8000/category/1/tasks/

Error Handing is done for status code 404 and 500
