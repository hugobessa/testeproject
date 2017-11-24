web: gunicorn testeproject.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=testeproject --loglevel=info
