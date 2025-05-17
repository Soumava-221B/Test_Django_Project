# Setup a Django Project
1. python3 -m venv .venv
2. source .venv/bin/activate
3. pip install django
4. pip freeze > requirements.txt
5. django-admin startproject xCopy
6. cd xCopy
7. python3 manage.py runserver
8. python3 manage.py makemigrations
9. python3 manage.py migrate
10. python3 manage.py createsuperuser
11. python manage.py startapp tweet