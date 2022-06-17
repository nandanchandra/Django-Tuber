release: python manage.py migrate

web: gunicorn tubers.wsgi --log-file -

worker: python manage.py rqworker default