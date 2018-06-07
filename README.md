# React-Django app
Simple setup for a React-Django web app.

## Requirements
- [Django](https://www.djangoproject.com/) and [Django rest framework](http://www.django-rest-framework.org/) for backend
- [React](https://facebook.github.io/react/) for frontend
- [npm](https://www.npmjs.com/get-npm)
- [pipenv](https://github.com/pypa/pipenv)

## Setup
- Create and activate virtual environment `pipenv --three && pipenv shell`
- Download/clone repo.
- Install Django depedencies `cd project && pipenv install`
- Install React depedencies `cd frontend && npm install`
- Run Django app using `python manage.py runserver`
- Run Django app and build React app `python manage.py runserver build`