# DjangoConcepts

Ref: https://synechron.udemy.com/python-django-dev-to-deployment/

Django is a high-level python framework that encourages rapid development.
There are two web framework in python:
  - Flask (low-level)
  - Django(high-level)
  
 What can be a better tutorial than trying it yourself. Django can be downloded from https://www.djangoproject.com/download/
 
 or 
 
 pip install Django==2.2.4
 
 Latest version when am writing this is 2.2.4
 
 Django tutorial: https://realpython.com/tutorials/django/
 
 check version : 
 $ python -m django --version

Django supports many different database servers and is officially supported with PostgreSQL, MySQL, Oracle and SQLite.

Applications¶
Django contains a registry of installed applications that stores configuration and provides introspection. It also maintains a list of available models.

This registry is simply called apps and it’s available in django.apps:

from django.apps import apps
apps.get_app_config('admin').verbose_name
- 'Administration'
