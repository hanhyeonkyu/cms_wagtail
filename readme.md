# CMS With Wagtail

## Starter

```zsh
# Create a virtual environment
python -m venv venv
# Activate the virtual environment
source venv/bin/activate
# Upgrade pip
pip install --upgrade pip
# Install Wagtail
pip install wagtail
# Create a new project
wagtail start myapp
# Go into the project
cd myapp
# Install requirements
pip install -r requirements.txt
# Run migrations
# sqlite3 default if you want to other database, modify DATABASES object in myapp/settings/base.py
python manage.py migrate
# Create superuser
python manage.py createsuperuser
# Run server
python manage.py runserver
# Open Website in browser
http://localhost:8000
# Open Admin Website in browser
http://localhost:8000/admin
```

## Custom

