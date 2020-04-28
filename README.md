# docker-django

Production ready Docker + Django + Bootstrap 4 starter pack.

Includes the following built in support for:

- **[`django-compressor`](https://github.com/django-compressor/django-compressor)**: Django Compressor processes, combines and minifies linked and inline Javascript or CSS in a Django template into cacheable static files. Supports such as CoffeeScript, LESS, and SASS.
- **[`django-dotenv`](https://github.com/jpadilla/django-dotenv)**: Allows `manage.py` to read environment settings stored in a `.env` file.
- **[`django-debug-toolbar`](https://github.com/jazzband/django-debug-toolbar)**: The Django Debug Toolbar is a configurable set of panels that display various debug information about the current request/response and when clicked, display more details about the panel's content.
- **[`djangorestframework`](https://www.django-rest-framework.org/)**: Django REST framework is a powerful and flexible toolkit for building Web APIs.
- **[`pillow`](https://pillow.readthedocs.io/en/stable/)**: Pillow is a friendly PIL fork. PIL is the Python Imaging Library by Fredrik Lundh and Contributors.
- **[`psycopg2-binary`](https://pypi.org/project/psycopg2-binary/)**: Stand-alone version of `psycopg2`, the most popular PostgreSQL database adapter for the Python programming language.
- **[`whitenoise`](http://whitenoise.evans.io/en/stable/)**: With a couple of lines of config WhiteNoise allows your web app to serve its own static files, making it a self-contained unit that can be deployed anywhere without relying on nginx, Amazon S3 or any other external service. Especially useful on Heroku, OpenShift and other PaaS providers.

## Build

```bash
docker build -t docker-django-image .
```

## Run

```bash
docker run --rm --name docker-django docker-django-image
```
