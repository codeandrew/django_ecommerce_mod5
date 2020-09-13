# Django eCommerce

## Virual env

Create a new Directory and cd into it.

mkdir test , cd test

Install and Create a Virtual environment.

python3 -m pip install virtualenv
virtualenv venv -p python3

Activate Virtual Environment: source venv/bin/activate

Install Django: pip install django

Start a new project: django-admin startproject myproject

cd to your project and Run Project:

cd myproject , python manage.py runserver

You can see your project here : http://127.0.0.1:8000/



## Setup

```bash
pip install django

python manage.py migrate
python -m pip install Pillow
```

## Administration

/admin
```
python manage.py createsuperuser
```

## Run application

```bash
python manage.py runserver
```

