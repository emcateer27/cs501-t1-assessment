web: gunicorn project.server:app
heroku ps:scale web=1
release: project/server/__init__.py db upgrade