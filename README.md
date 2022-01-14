# Django-ToDoListApp

This is a basic to-do list web app made with [Python](https://www.python.org/) using the [Django](https://www.djangoproject.com/) framework.
You can add, edit and remove items from the list.

## Install

This project uses a [MySQL](https://www.mysql.com/) database to store the items on the to-do list.
Using [pip](https://pypi.org/project/pip/) you can install the required packages.

[Download Python](https://www.python.org/downloads/).

Install pip using
```
pip install pip
```
Install Django using
```
python -m pip install Django
```

## Usage

  * Clone the repository
  * Create a virtual environment
    ```
    python -m venv venv
    ```
  * Activate the virtual environment
    ```
    source venv/bin/activate
    ```
  * Install the required packages
    ```
    pip install -r requirements.txt
    ```
  * Start migrations with the following two lines
    ```
    python manage.py makemigrations
    python manage.py migrate
    ```
  * Run the server
    ```
    python manage.py runserver
    ```
