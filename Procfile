web: uwsgi --ini=uwsgi.ini --http=0.0.0.0:$PORT -p1
smart-attach-daemon = sentry --config=sentry.conf.py celery worker --loglevel=INFO
smart-attach-daemon = sentry --config=sentry.conf.py celery beat --loglevel=INFO
