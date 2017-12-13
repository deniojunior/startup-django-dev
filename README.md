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
* Include app_name in array INSTALLED_APP.
* Edit LANGUAGE_CODE to your language.
* Edite TIME_ZONE to your timezone.


# Migrate
Create database structure
```bash
py manage.py migrate
```

After edit models.py, adding the model classes, run:
```bash
py manage.py makemigration app_name
py manage.py migrate
```

# Shell
Python environment with project context
```bash
py manage.py shell
```

# Run Server
```bash
py manage.py runserver
```

After that, access localhost:8000
