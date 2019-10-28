# DJANGO-REST-FRAMEWORK-CRUDE-APPLICATION
 Simple crude application developed using Django & REST framework

Initial Setup
Let’s start by creating a directory for our code, installing Django, and creating a new project. Execute the following on the command line.


pip install django==2.2.5
pip shell
django-admin startproject todo_project (project)
python manage.py startapp todos (1st APP)
python manage.py startapp apis (2nd APP)

urls :
1. to access the complete project:
http://127.0.0.1:8000/apis/v1/ 

2. to acces particular id/content:
http://127.0.0.1:8000/apis/v1/<id>/
