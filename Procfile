web: gunicorn pizzamama.wsgi --log-file -
release: python manage.py migrate --noinput && python manage.py loaddata menu/fixtures/pizzas.json
