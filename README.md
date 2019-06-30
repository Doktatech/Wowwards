# Wowwards
A web application which allows users to review other developers work.

## User stories

The user should be able to:

+ [x] View posted projects and their details.
+ [x] Post a project to be rated/reviewed
+ [x] Rate/ review other users' projects.
+ [x] Search for projects.
+ [x] View projects overall score
+ [x] View my profile page.

## Prerequisites
+ [x] Python3.6.7

## Installation
To install, follow the following instructions;

```bash
    $ https://github.com/Doktatech/Wowwards.git
    $ cd Wowwards
    $ source virtual/bin/activate
    Install all the necessary requirements by running pip install -r requirements.txt (Python 3.6).
    $ ./manager.py runserver
```
## Setting up the  enviroment variables
create a .env file in the root folder and add the following variables in it.

```bash
    SECRET_KEY= #secret key will be added by default
    DEBUG= #set to false in production
    DB_NAME= #database name
    DB_USER= #database user
    DB_PASSWORD=#database password
    DB_HOST="127.0.0.1"
    MODE= # dev or prod , set to prod during production
    ALLOWED_HOSTS='.localhost', '.herokuapp.com', '.127.0.0.1'
```
## Wowwards Demo

This is the live link to the application [Click here]

## Known Bugs
	There are no known bugs as of the latest update

## Technology used

* [Python3.6.7](https://www.python.org/)
* [Django 1.11](https://www.djangoproject.com/)
* [Bootstrap](https://www.getbootstrap.com/)
* [Heroku](https://heroku.com)
 

## License ([MIT License](https://github.com/Doktatech/Wowwards/blob/master/LICENSE))
This project is licensed under the MIT Open Source license, (c) [Rewel Kinyanjui](https://github.com/Doktatech)
