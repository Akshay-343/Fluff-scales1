# Fluff & Scales

A Django e-commerce web app for a pet supplies store, built as a test/learning project.

## Features

- Product catalogue with search and filtering
- Shopping cart
- User authentication (register, login)
- Admin panel for product management

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Django 4.2, SQLite |
| Frontend | Bootstrap 5, crispy-forms |
| Images | Pillow |
| Deploy | Vercel (vercel.json included) |

## Setup

```bash
python -m venv .venv
.venv\Scripts\activate      # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Set `DJANGO_SECRET_KEY` in your environment before deploying.
