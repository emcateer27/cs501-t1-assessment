web: gunicorn project.server:app
heroku ps:scale web=1
release: heroku run flask db upgrade