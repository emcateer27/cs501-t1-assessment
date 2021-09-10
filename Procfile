web: gunicorn project.server:app
heroku ps:scale web=1
release: python project.server.__init__ db upgrade

