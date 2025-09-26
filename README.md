# Social Book - Learning App

This is my learning project to practice Django by building a simple social media application called "Social Book". The app allows users to create accounts, post updates, and interact with each other.

Based on this video: https://www.youtube.com/watch?v=xSUm6iMtREA

## Getting started

- Setup a virtual environment (optional but recommended):

  ```bash
  py -m venv social_book_proj
  social_book_proj\Scripts\activate
  ```

- Install Django and other dependencies:

  ```bash
  py -m pip install Django
  django-admin --version
  ```

- Create a new Django project:

  ```bash
  django-admin startproject social_book .
  ```

- Create a new Django app:

  ```bash
  django-admin startapp core
  ```

- Add the app to the project's settings:

  ```python
  # social_book/settings.py

  INSTALLED_APPS = [
      ...
      'core',
  ]
  ```

- Run the development server to ensure everything is set up correctly:

  ```bash
  py .\manage.py runserver
  ```

- Install Pillow for image handling:

  ```bash
  py -m pip install Pillow
  ```

- Make migrations and migrate the database:

  ```bash
  py .\manage.py makemigrations
  py .\manage.py migrate
  ```

- Create a superuser to access the admin panel:

  ```bash
  py .\manage.py createsuperuser
  ```
