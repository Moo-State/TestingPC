release: python manage.py migrate
web: gunicorn config.wsgi:application
worker: celery worker --app=ProcessMining.taskapp --loglevel=info
