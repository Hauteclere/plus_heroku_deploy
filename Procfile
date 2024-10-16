release: python manage.py migrate
web: gunicorn --pythonpath crowdfunding crowdfunding.wsgi --log-file -
