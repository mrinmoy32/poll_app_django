# Poll App Django

This repository contains a basic Django poll application. It allows users to create polls with multiple choices and vote on them.

## Features

- Create and manage polls
- Vote on poll questions
- View poll results

## Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

- Python 3.x
- Django 5.0

### Clone the Repository

```bash
git clone https://github.com/mrinmoy32/poll_app_django.git
cd poll_app_django
```

### Set Up the Virtual Environment

It's a good practice to use a virtual environment to manage dependencies. Run the following commands to set up a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Install Django

Since there is no `requirements.txt` file, you need to manually install Django:

```bash
pip install django
```

### Install Django Debug Toolbar (Optional)

If you want to use Django Debug Toolbar for debugging, install it using:

```bash
pip install django-debug-toolbar
```

Refer to the [Django Debug Toolbar Installation Guide](https://django-debug-toolbar.readthedocs.io/en/latest/installation.html) for more details.

### Migrate Database

Run the following commands to apply migrations and set up the database:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Create a Superuser

Create a superuser to access the Django admin interface:

```bash
python manage.py createsuperuser
```

Follow the prompts to set up your superuser account.

### Run the Development Server

Start the Django development server:

```bash
python manage.py runserver
```

Open your web browser and go to `http://127.0.0.1:8000` to see the application in action.

## Usage

- Access the Django admin at `http://127.0.0.1:8000/admin` to create and manage polls.
- The main application will be accessible at `http://127.0.0.1:8000/polls`.

## References

- Official Django Documentation: [Django Tutorial](https://docs.djangoproject.com/en/5.0/intro/tutorial01)
- Django Debug Toolbar: [Installation Guide](https://django-debug-toolbar.readthedocs.io/en/latest/installation.html)
- Github Django admin default template directory: [Default Django Admin Templates](https://github.com/django/django/blob/main/django/contrib/admin/templates/admin/base_site.html)

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

