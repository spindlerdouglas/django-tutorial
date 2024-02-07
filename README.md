Brief step-by-step description on how to setup a new Django project:

1. Create a virtual environment using **'python -m venv <name-of-virtual-environment>'**
2. Activate the environment
3. In the root folder, create the Django project using **'django-admin startproject <project-name> .'** 
4. Create the desired apps within the project by executing **'python manage.py startapp <app-name>'**
5. Add the corresponding URL paths and views in the *urls.py* and *views.py* files
6. To run the server, execute **'python manage.py runserver'**