# setup
- create virtual environment and run `pip install -r requirements` on it
- run `python manage.py migrate`
- run `python manage.py runserver` in one terminal
- run `daphne Config.asgi:channel_layer --port 8888` in a different terminal