# DjangoBlog

[![Build Status](https://travis-ci.org/Tony133/DjangoBlog.svg?branch=master)](https://travis-ci.org/Tony133/DjangoBlog)

Simple Example Blog with Django 1.11 LTS

## Create Virtual Environment

```
    $ python -m venv myvenv or python3 -m venv myvenv
```
## Start up Environment

```
    $ source myvenv/bin/activate
```
## Install Django

```
    $ pip install django==1.11
```

## Getting Migrate Table on database

```
    $ python manage.py migrate
```

## Create SuperUser for Admin

```
    $ python manage.py createsuperuser
```

## Getting Fixtures

```
    $ python manage.py loaddata data.json 
```

## Run App
```
    $ python manage.py runserver
```
