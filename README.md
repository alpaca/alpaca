Alpaca
======

This repository is a collection of open source tools that power our business, [Alpaca.io](http://alpaca.io/).

## Our Team
* Al Johri - [aljohri](https://github.com/AlJohri) - [al.johri@gmail.com](al.johri@gmail.com)
* Moritz Gellner - [moritzg91](https://github.com/moritzg91) - [moritz.gellner@gmail.com](moritz.gellner@gmail.com)
* Carson Potter - [cpottamus](https://github.com/cpottamus) - [cp3192@gmail.com](cp3192@gmail.com)
* Dhrumil Mehta - [dmil](https://github.com/dmil) - [dhrumil.mehta@gmail.com](dhrumil.mehta@gmail.com)
* Sergio Hidalgo - [GeorgeMaharis](https://github.com/GeorgeMaharis) - [sergiochidalgo@gmail.com](sergiochidalgo@gmail.com)
* Daniel Thirman - [dthirman](https://github.com/DThirman) - [dthirman@gmail.com](dthirman@gmail.com)

Code Organization
-----------------

### Documentation and Coding Practices

- https://github.com/alpaca/alpaca - point of entry for the Alpaca organization

### Services
- https://github.com/alpaca/api - wires up all the python packages together
- https://github.com/alpaca/frontend - user facing frontend for the api

### Templates and Generators
- https://github.com/alpaca/flask-template - best practices we've come up with for flask
- https://github.com/alpaca/tornado-template - best practices we'e come up with for tornado
- https://github.com/alpaca/generator-alpaca-flask - yeoman generator for flask
- https://github.com/alpaca/generator-alpaca-tornado - yeoman generator for tornado

### Python Packages
- https://github.com/alpaca/socialscraper - scrape Facebook and Twitter
- https://github.com/alpaca/identityresolver - wraps around the Pipl API
- https://github.com/alpaca/mixturemodel - does GMM clustering/classification

Alpaca Templates
-----------------

### Installing Alpaca Templates

    npm install -g yo yeoman-generator
    npm install -g git+ssh://git@github.com/alpaca/generator-alpaca-flask
    npm install -g git+ssh://git@github.com/alpaca/generator-alpaca-tornado

### Using Alpaca Templates

    yo alpaca-flask
    yo alapca-tornado

Our Favorite Technologies
-------------------------

This list isn't exhaustive by any means.
- Python 2.7.6+
  - Requests - https://github.com/kennethreitz/requests
  - SQLAlchemy - https://github.com/zzzeek/sqlalchemy
  - Celery - https://github.com/celery/celery
    - Flower - https://github.com/mher/flower
  - Flask - https://github.com/mitsuhiko/flask
    - Flask-SQLAlchemy - https://github.com/mitsuhiko/flask-sqlalchemy
    - Flask-Migrate - https://github.com/miguelgrinberg/Flask-Migrate
    - Flask-RESTful - https://github.com/twilio/flask-restful
    - Flask-Script - https://github.com/smurfix/flask-script
    - Flask-Testing - https://github.com/jarus/flask-testing
  - lxml - https://github.com/lxml/lxml
  - BeautifulSoup4 - https://github.com/kelp404/bs4
- Dokku https://github.com/progrium/dokku
  - https://github.com/progrium/buildstep
  - Docker https://github.com/dotcloud/docker
