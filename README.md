# mordern-drf-django-backend-setup
Modern Django DRF Setup: A simple way to initialize Rest API project in Django.


## Requirements

1.  Python 3+
2.  Django 3+
3.  Django REST Framework


## Installation on Development Machine

To run the app on your local machine, you need Python 3+, installed on your computer. If you using pipenv than follow 6 steps

1.  Create and activate `pipenv` virtual environment:

        pipenv shell

2.  Read pipenv file:
    ```shell
    pipenv install --dev --pre
    ```
3)  Copy `env.example` to `.env` file:
    In terminal
    `shell cp .env.example .env`

        then put all key values in .env file

4)  Migrate

    ```shell
    python manage.py migrate
    ```
5)  Create SuperUser
    ```shell
    python manage.py createsuperuser
    ```

6)  Run server
    ```shell
    python manage.py runserver
    ```