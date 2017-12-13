# startup-django-dev

# Install
Supposing you have python installed, install django framework using pip
```bash
pip install django
```

# New Project
```bash
django-admin startproject project_name
cd project_name/
py manage.py startapp app_name
```

# Config settings.py
* Include project_name in array INSTALLED_APP.
* Edit LANGUAGE_CODE to your language.
* Edite TIME_ZONE to your timezone.


# Migrate
Create database structure
```bash
py manage.py migrate
```

# Run Server
```bash
py manage.py runserver
```

After that, access localhost:8000
