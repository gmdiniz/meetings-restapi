release: python manage.py migrate
web: gunicorn meetings-restapi.wsgi:application --log-file=-- --log-level debug
