web: gunicorn project.server:__init__
heroku ps:scale web=1
release: python project/server/__init__.py db upgrade