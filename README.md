# My Details - Django App

Simple Django app that shows Karan Tanwar's profile.

Prerequisites
- Python 3.10+ (or compatible)
- pip

Setup (PowerShell)

```powershell
cd "e:\Projects\Django application\mydetails_project"
python -m venv .venv; .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Open http://127.0.0.1:8000/ to view the profile.
