## ibx-flask-app

Flask Application for the Fly cloud deployment

# Components:
- [Flask](https://github.com/pallets/flask) - Python micro framework
- [Gunicorn](https://gunicorn.org) - 'Green Unicorn' is a Python WSGI HTTP Server for UNIX

# Deployment:
0. [Fly.io](https://fly.io) - create account
1. mkdir ibx-flask-app
2. cd ibx-flask-app
3. python -m venv venv
4. .\venv\scripts\activate
5. pip install flask, gunicorn
6. create app.py, template and wsgi.py
7. some code
8. pip freeze > requirements.tx
9. flyctl auth login
10. flyctl launch
11. flyctl deploy
12. browse https://ibx-flask-app.fly.dev/
