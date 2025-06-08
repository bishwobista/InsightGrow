# Django Project Setup: Step by Step

## 1. Install Python
Ensure Python 3.x is installed.  
Check with:
```bash
python3 --version
```

## 2. Create a Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

## 3. Install Django
```bash
pip install django
```

## 4. Start a New Django Project
```bash
django-admin startproject myproject
cd myproject
```

## 5. Run Development Server
```bash
python manage.py runserver
```
Visit `http://127.0.0.1:8000/` in your browser.

## 6. Create a Django App
```bash
python manage.py startapp myapp
```

## 7. Register the App
Add `'myapp'` to `INSTALLED_APPS` in `myproject/settings.py`.

## 8. Make Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```

## 9. Create a Superuser
```bash
python manage.py createsuperuser
```

## 10. Start Building!
Edit `views.py`, `urls.py`, and templates as needed.
