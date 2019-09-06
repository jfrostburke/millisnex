release: cat requirements_test.txt | xargs -n 1 -L 1 pip install && python manage.py migrate --noinput
web: gunicorn snex2.wsgi
