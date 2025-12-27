# OctoFit Tracker — Backend

This folder will contain the Django backend for the OctoFit Tracker app.

Setup steps (recommended):

1. Create a Python virtual environment (from repo root):

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
```

2. Install requirements:

```bash
pip install -r octofit-tracker/backend/requirements.txt
```

3. Initialize the Django project (if not already done):

```bash
django-admin startproject octofit_tracker .
python manage.py startapp core
```

4. Use Django ORM to manage models. See `.github/instructions` for project guidelines.
