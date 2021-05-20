# DjangoBlogApp
A Minimalistic Blogging App built using Python (Django Web Application Framework).

# Prerequistes
- Python Version 3.xx should be installed into your system
- Install Django framework if not installed already
               
          pip install Django

# How to Run the Application
- Clone the repository
- `cd` to the same directory where the directory is cloned
- It is ideal to create a Virtual environment to install all the dependencies and run the project in. Run the following command in command prompt:
     
          python -m venv Env

- Activate the Virtual enviroment by the following command:
          
          c://users/hp/desktop/python/venv/scripts/activate

where, `Env` is the name of your Virtual environment

- Follow next step, If requirements.txt is already available or generate requirements.txt using:
     
        pip freeze > requirements.txt

- Install all the dependencies/requirements:

        pip install requirements.txt

- Run the server by running the following:
     
        python manage.py runserver

The server should now be running at `127.0.0.1:8000`

# Functionalities
- User Registration
- Blog Functionality
    - Creation of New Posts 
    - Edit and Deletion of Posts
- User Profile
    - New Profile Creation
    - Profile Updation
- Login and Logout Functionality

# Upcoming Features
- User Comments
- Fix heroku deployment CORS issues

# Current To-do
Since the files present are compiled python files (.pyc files), it is important to have the source files (.py files) to be able to make further changes. If anyone wants to uncompile the files, feel free to create a pull request.
- I've already tried to decompile with [decompyle3](https://github.com/rocky/python-decompile3) by downgrading to the decompyle compatible Python version 3.8.
- The possible outlook on this is the compiled files being Python 3.9. 
