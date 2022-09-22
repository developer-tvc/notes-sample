# NOTES web application

[![License: MIT](https://img.shields.io/github/license/vintasoftware/django-react-boilerplate.svg)](LICENSE.txt)

## About

Notes web application

- A [DjangoREST](https://www.django-rest-framework.org/) project with lots of state of the art libraries and tools like:
- [React](https://facebook.github.io/react/), for building interactive UIs

## Setup

### Requirements:
- Node: v16.15.0
- Python: 3.8

### Frontend Setup:
- Add env files `.env`(ReactJS)
- Make sure node version by `node -v`
- `npm install` to install javascript libraries

### Backend Setup
- Add env files `project/.env`(Django)
- create and activate virtual environment in Python 3.8
- `pip install -r requirements.txt` to install python modules
- `python manage.py makemigrations`
- `python manage.py migrate`
- create superuser if needed

### Running in development mode
Frontend 

- `npm start`
Access frontend `http://localhost:3000`

Backend

- `python manage.py runserver`
backend default url `http://localhost:8000`
