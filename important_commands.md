# Important Commands and Setup Instructions for Poll App Django Project

Follow these Commands to set up and run the Django poll app project.

## Prerequisites

Make sure you have the following installed:

- Python 3.6+
- Pipenv

## Step-by-Step Instructions

1. **Check the versions of Django and Pipenv:**
    ```sh
    python -m django --version
    pipenv -v
    ```

2. **Install Pipenv:**
    ```sh
    pip install pipenv
    ```

3. **Install Django using Pipenv:**
    ```sh
    pipenv install django
    ```

4. **Activate the Pipenv shell:**
    ```sh
    pipenv shell
    ```

5. **Start a new Django project:**
    ```sh
    django-admin startproject poll_app .
    ```

6. **Run the development server to check if everything is set up correctly:**
    ```sh
    python manage.py runserver
    ```

7. **Create a new app named "polls":**
    ```sh
    python manage.py startapp polls
    ```

8. **Install additional dependencies (e.g., aiohttp):**
    ```sh
    pip install aiohttp
    ```

9. **List installed packages:**
    ```sh
    pip list
    ```

10. **Create initial migrations for the "polls" app:**
    ```sh
    python manage.py sqlmigrate polls 0001
    ```

11. **Apply the migrations:**
    ```sh
    python manage.py migrate
    ```

12. **Create new migrations for any changes in the "polls" app models:**
    ```sh
    python manage.py makemigrations polls
    ```

13. **Open the Django shell:**
    ```sh
    python manage.py shell
    ```

14. **Create a superuser for accessing the Django admin interface:**
    ```sh
    python manage.py createsuperuser
    ```

15. **Install Django Debug Toolbar:**
    ```sh
    python -m pip install django-debug-toolbar
    ```

16. **Run tests for the "polls" app:**
    ```sh
    python manage.py test polls
    ```

## Notes

- Make sure to configure your database settings in `poll_app/settings.py` if you plan to use a database other than SQLite.

