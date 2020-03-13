# Creating a Custom User Model in Django

1. *How do I fully replace the username field with an email field for Django authentication?*
1. `AbstractUser` vs `AbstractBaseUser`

## Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/django-custom-user-model/).

## Want to use this project?

1. Fork/Clone

1. Pick one: `AbstractUser` or `AbstractBaseUser`

1. Run:

    ```sh
    $ python3 -m venv env && source env/bin/activate
    (env)$ pip install django==3.0.4
    (env)$ python manage.py makemigrations
    (env)$ python manage.py migrate
    (env)$ python manage.py runserver
    ```
