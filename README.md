# 2poundsmeal
Food Intake Analysis Application

This prototype page was developed to visualise the concept of 2poundsmeal’s application. The application, combined with VIsual recognition technology of IBM Watson and Clouding technology, will allow users to identify the nutrient content of their food intake from the food photos they provide.

We only provide data on branded foods around £3 that students can see around Sheffield University.
- Tesco sandwiches
- Sainsbury’s sandwiches
- Domino Pizza Personal Pizza - KFC Burgers
- Subway 6” Sub
- McDonalds Burgers

## How to use
- Upload food picture
- Insert your basic information
- Check the recognition result
- Identify excess / deficient nutrients

##
This application supports the [Getting Started with Python on Heroku](https://devcenter.heroku.com/articles/getting-started-with-python) article - check it out.

## Running Locally

Make sure you have Python 3.7 [installed locally](http://install.python-guide.org). To push to Heroku, you'll need to install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli), as well as [Postgres](https://devcenter.heroku.com/articles/heroku-postgresql#local-setup).

```sh
$ git clone https://github.com/heroku/python-getting-started.git
$ cd python-getting-started

$ python3 -m venv getting-started
$ pip install -r requirements.txt

$ createdb python_getting_started

$ python manage.py migrate
$ python manage.py collectstatic

$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku master

$ heroku run python manage.py migrate
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Documentation

For more information about using Python on Heroku, see these Dev Center articles:

- [Python on Heroku](https://devcenter.heroku.com/categories/python)

## Built With
- IBM Watson - Visual recognition 
- IBM Cloud – Food nutrition data

## Authors
- Jinhyuk Kim - Project Director
- Da Eun Kim - Front/Backend Developer
