# Django Starter Project

This repository contains a minimal Django configuration with a simple home page.

## Getting Started

1. Create a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
2. Apply database migrations and run the development server:
   ```bash
   python manage.py migrate
   python manage.py runserver 0.0.0.0:8000
   ```
3. Open http://localhost:8000/ to see the home page.

Environment variables like `DJANGO_SECRET_KEY`, `DJANGO_DEBUG`, and `DJANGO_ALLOWED_HOSTS` can be used to customize runtime behavior.
