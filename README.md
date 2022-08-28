## ibx-flask-app

Flask Application for the Fly cloud deployment

# Components
- Flask
- gunicorn

# Deployment
1- mkdir ibx-flask-app
2- cd ibx-flask-app
3- python -m venv venv
4- .\venv\scripts\activate
5- pip install flask, gunicorn
6- create app.py, template and wsgi.py
7- some code
8- flyctl auth login
9- flyctl launch
10- flyctl deploy
11- browse https://ibx-flask-app.fly.dev/