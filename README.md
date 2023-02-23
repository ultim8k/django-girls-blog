# README

Create project:

```sh
django-admin startproject mysite .
```

Create/Update DB:

```sh
python manage.py migrate
```

Start server:

```sh
python manage.py runserver
```

Visit [127.0.0.1:8000](http://127.0.0.1:8000/)

Create app:

```sh
python manage.py startapp blog
```

Create DB structure from models:

```sh
python manage.py makemigrations blog
```

Apply migrations:

```sh
python manage.py migrate blog
```

Create super user:

```sh
python manage.py createsuperuser
```
