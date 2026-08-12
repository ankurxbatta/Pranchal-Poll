# Pollster — a polling app

A web app for creating polls and voting on them: each question offers a set of
choices, people vote, and the running tally is shown. Built with **Django**,
following the classic Django polls structure.

## What it does

- Questions, each with multiple choices (`polls/models.py`)
- Vote on a question and see results update
- Django admin for creating and managing polls (`polls/admin.py`)

## Repository layout

```
pollster/       Django project (settings, URLs, WSGI/ASGI)
polls/          the app — models, views, admin, migrations
manage.py
db.sqlite3      development database
```

## Running it

```bash
python3 manage.py migrate
python3 manage.py createsuperuser   # to add polls via /admin
python3 manage.py runserver
```

Then open http://localhost:8000.

## Built with

Python, Django and SQLite.
