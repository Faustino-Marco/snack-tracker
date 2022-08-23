# LAB - Class 26
## Project: Intro to Django
#### Author: Faustino Marco Simpliciano

### Links and Resources
- Development server: http://127.0.0.1:8000/
- front-end application: "Snacks"

### Feature Tasks & Requirements 08/23
- Create web site in Django with 2 pages
    - home page
    - about page
    - create views/urls/templates as needed for home and about pages
    - use ancestor template to contain navigation elements
    - Should be built the "Django Way"
        - Match the structure of in-class demo

### Typical Steps to Start Django Project
- create project
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
