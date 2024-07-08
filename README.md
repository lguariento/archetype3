# ARCHETYPE3

## Quick Start (Development)

Create a Python3 virtual environment and activate it:

    python3 -mvenv venv
    source venv/bin/activate
    pip install -r requirements.txt

Create the initial database:

    python manage.py migrate

Create an admin user:

    python manage.py createsuperuser

Run:

    python manage.py runserver 0.0.0.0:8000

Test:

    http://localhost:8000
    http://localhost:8000/admin/
    http://localhost:8000/django-admin/

## Deployment (Web Server)

    ...
