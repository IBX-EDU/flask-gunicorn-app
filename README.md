## ibx-flask-gunicorn-app

Flask + Gunicorn Application for the Fly.io cloud deployment

# Components:
- [Flask](https://github.com/pallets/flask): The Python micro framework for building web applications.
- [Gunicorn](https://gunicorn.org): 'Green Unicorn' is a Python WSGI HTTP Server for UNIX.
- [Fly.io](https://fly.io): Fly is a platform for running full stack apps and databases.

# Deployment:
0. [Fly.io](https://fly.io) - create account
1. mkdir ibx-flask-gunicorn-app
2. cd ibx-flask-gunicorn-app
3. python -m venv venv
4. .\venv\scripts\activate
5. pip install flask, gunicorn
6. create app.py, template and wsgi.py
7. some code
8. pip freeze > requirements.tx
9. flyctl auth login
10. flyctl launch
11. configure Procfile
12. flyctl deploy
13. browse https://ibx-flask-gunicorn-app.fly.dev/
