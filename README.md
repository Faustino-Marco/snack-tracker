# LAB - Class 27
## Project: Django Models
#### Author: Faustino Marco Simpliciano

### Links and Resources
- Development server: http://127.0.0.1:8000/
- front-end application: "Snack Tracker"

### Feature Tasks & Requirements 08/23
- Build out a project with one model and wire up that model using Django Views.
  - create snack_tracker_project
  - crea

### Typical Steps to Start Django Project
- create project
  - `django-admin startproject name_name_name .`
    - DON'T FORGET THE `.`
  - `python manage.py runserver`
    - if working, now migrate
  - `python manage.py migrate`
  - `python manage.py startapp name_`
  -> views.py
    - SEE VIEWS IN DEMOOOO
  -> models.py
    - `class N_ame(models.Model):`
      - name = models.CharField(max_length=256)
  - `python manage.py createsuperuser`
    - usrnm
    - email
    - pswd
  - go to admin path to login on dev server
  - see admin.py
    - `from .models import Snack`
    - `admin.site.register(Snack)`
  - `python manage.py showmigrations`
    - `python manage.py makemigrations name_of_app`
    - repeat show migrations cmd
    - runserver
    - use cmd to apply new migration
  - create urls.py in app
    - copy over from urls.py in project dir
- define app
- add app to project
- add views
- add urlpatterns
- add templates
- add tests

### Setup
<!-- .env requirements (where applicable) -->
- requirements.txt
- .gitignore populated using [this](https://www.toptal.com/developers/gitignore/api/python,windows) template.
<!-- 
- PORT - Port Number
- DATABASE_URL - URL to the running Postgres instance/db -->
- How to initialize/run your application (where applicable) e.g. python main.py
  - `python manage.py runserver`
- How to use your library (where applicable)
- Tests
  - How do you run tests?
    - `python manage.py test`
  - Any tests of note?
    - Homepage status code
    - About page status code
    - Homepage use of template
    - About page use of template
  - Describe any tests that you did not complete, skipped, etc
    - N/A
