# Django Girls
Django site created by tutorial on: :heart: https://tutorial.djangogirls.org/
## What do you need to start?
* Install python
* Install venv
```
python -m venv myvenv
```
* Activate myvenv
```
myvenv\Scripts\activate
```
* Install pip
```
python -m pip install --upgrade pip
```
* Install django
```
python pip install django~=1.11.0
```
* Start Django project(if empty)
```
django-admin startproject mysite .
```
* Create database for Django site
```
python manage.py migrate
```
* Run our site
```
python manage.py runserver
```
* Add blog site(create app) - no need(for history)
```
python manage.py startapp blog
```
* Add models in database(only first time)
```
python manage.py makemigrations blog
```
* Apply migration(s)
```
python manage.py migrate
```
* Create superuser
```
python manage.py createsuperuser
```
