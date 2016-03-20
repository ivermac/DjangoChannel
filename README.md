This repo is based on [this tutorial](https://blog.heroku.com/archives/2016/3/17/in_deep_with_django_channels_the_future_of_real_time_apps_in_django)

# setup
- create virtual environment and run `pip install -r requirements` on it
- run `python manage.py migrate`
- run `python manage.py runserver` in one terminal
- run `daphne Config.asgi:channel_layer --port 8888` in a different terminal

# note
test `python manage.py runworker`
