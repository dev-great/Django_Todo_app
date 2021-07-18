# Getting started
ToDo App is simple and awesome app to organize your tasks with very easy to use interface. 
This app has ability for user login , add/delete todos, add/delete calendar events and managing todos and events.

# Prerequisites
Install pip if it is not installed yet in your system

To install virtual environment, run in your terminal:

pip install virtualenv
To create a virtual environment, in the root folder of the cloned app, run:
virtualenv -p python3 venv
To activate the virtualenv:
source venv/bin/activate
Run the command below to install all the project dependencies:
pip install -r requirements.txt
To deactivate the virtualenv:
deactivate
Installing

# Clone the project repository
$ git clone https://github.com/dev-great/Django_Todo_app.git
Cd into the cloned app, create a virtualenv and activate(see instruction above for steps to create a virtualenv)

Create a .env file, copy the variables in the .env_sample in the root directory of the project and set up the configurations according to your system.

Ensure to makemigrations then migrate by running the following commands sequencially:

- python manage.py makemigrations

- python manage.py migrate

# Run Django Server
$ cd todo-list/
$ python manage.py migrate
$ python manage.py runserver
Features
User login system
Todo lists
Calender Event Management
Contributing
I love contributions, so please feel free to fix bugs, improve things, provide documentation. Just send a pull request.
