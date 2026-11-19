# DormSecure — Dormitory Web Application

A group project developed with **Python, Flask and SQLite**. DormSecure provides account management and a request workflow for dormitory residents and owners.

## Core features
- Account signup and login
- Guest and owner roles
- Residents can submit requests related to their building, floor and room
- Owners can review and manage requests
- Request status pages

## Tech stack
- **Backend:** Python 3, Flask
- **Database:** SQLite
- **Frontend:** HTML templates, CSS
- **Deployment:** Gunicorn / Procfile

## Run locally
```bash
python -m venv .venv
# Activate the virtual environment for your OS
pip install -r requirements.txt
python app.py
```

Open the local URL printed by Flask.

## Project structure
- `app.py` — Flask routes, database creation and request logic
- `templates/` — HTML pages
- `static/` — frontend assets
- `requirements.txt` — Python dependencies
- `Procfile` — deployment entry point

## Project links
- [Deployment](https://dormsecure-297e888332bb.herokuapp.com/) (availability not verified)
- [Project report](https://docs.google.com/document/d/1n7AHMCy5Db5Mo6lWQ7gJHon4AbRxuJVvFmKdeQIjUZI/edit?tab=t.0/)

## Team
DormSecure was developed as a student team project at KMITL. Original team credits:
- Thitipat Nontaphet
- Watthikon Julpan
- Apisit Nunkaew
- Pratchaya Phianphon

> **Security note:** This is a coursework demo. Before any production use, replace placeholder secret keys, remove hard-coded demo credentials and review authentication, data validation and deployment configuration.
