# Django Pollster Project

This is the project that comes as a result from following the basic tutorial found on the Django web page.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

- Get the latest edition of Python on your computer
- Install pip
- Install pipenv 
```pip install pipenv```
- Install Django
```pipenv install django```
- Get the code by cloning this repository into your local device (using git, or github for desktop)
- Migrate to sqlite database
```python manage.py migrate```

### Installing

- Start a python environment with pipenv 
```pipenv shell```
- Start up the webserver
```python manage.py runserver```
- Connect to ```localhost:8000``` on a web browser

### Making Questions for Pollster

- Create a super user
```python manage.py createsuperuser```
- Connect to the admin page ```localhost:8000/admin``` on a web browser
- In the Questions section, you can edit the questions and the choices. The app will store these on the sqlite database.

## Built With

* [Django](https://www.djangoproject.com/) - The web framework used
* [Python](https://www.python.org/) - The programming language used
* [VScode](https://code.visualstudio.com/) - The super-good code editor used

## Authors

* **Andy Qu** - *Initial work* - [toastymcvoid](https://github.com/toastymcvoid)

## Acknowledgments

* Hat tip to anyone whose code was used
* You can actually make this entire project yourself by following this [link](https://docs.djangoproject.com/en/3.0/intro/tutorial01/)
