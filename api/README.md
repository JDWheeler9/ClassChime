# Django API
Django intro docs: https://docs.djangoproject.com/en/5.0/intro/tutorial01/

## Versions:
Python 3.12.3
https://www.python.org/downloads/release/python-3123/

Django 5.0.6
`pip install Django==5.0.6`

### Starting the Django dev web server:
```
python manage.py runserver
```
Navigate to  http://127.0.0.1:8000/

Note from docs: You’ve started the Django development server, a lightweight web server written purely in Python. We’ve included this with Django so you can develop things rapidly, without having to deal with configuring a production server – such as Apache – until you’re ready for production. Don’t use this server in anything resembling a production environment. It’s intended only for use while developing. (We’re in the business of making web frameworks, not web servers.)

The development server automatically reloads Python code for each request as needed. You don’t need to restart the server for code changes to take effect. However, some actions like adding files don’t trigger a restart, so you’ll have to restart the server in these cases.