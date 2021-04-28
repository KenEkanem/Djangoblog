# Blog

Live [heroku] ()

## Features
- A register page (a new user can register, their details stored in a database file). 

- login (checks in the file and logs them in if they are already registered)

- reset password

- logout

- A comment section, you must be logged in to comment

Requirements
_python installation_

## Make it your own
- Clone the repository

    `git clone https://github.com/KenEkanem/Djangoblog.git`

- Create your own virtual environment

- Install the requirements

- Rename the project
Rename the directory that contains settings.py.
Do a find all and replace to rename all instances of the new project name.

- Make your migrations
The only migrations that should appear in each of your app’s migrations folders are called ‘__init__.py’. As we have started a new database, we can delete any existing migrations and migrate from scratch.

In your terminal:
    `$ python manage.py makemigrations`
    `$ python manage.py migrate`

- Create a new superuser
    `python manage.py createsuperuser`

- Final checks
Start the development server
    `python manage.py runserver`






