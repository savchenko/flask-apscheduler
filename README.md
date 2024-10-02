# Flask-APScheduler

Flask-APScheduler is a Flask extension which adds support for the
APScheduler.

[![Version](https://img.shields.io/pypi/v/flask-apscheduler.svg)](https://pypi.python.org/pypi/Flask-APScheduler)
[![Tests](https://github.com/viniciuschiele/flask-apscheduler/actions/workflows/tests.yml/badge.svg)](https://github.com/viniciuschiele/flask-apscheduler/actions/workflows/tests.yml)
[![Coverage](https://codecov.io/github/viniciuschiele/flask-apscheduler/coverage.svg)](https://codecov.io/github/viniciuschiele/flask-apscheduler)
[![Docs](https://github.com/viniciuschiele/flask-apscheduler/actions/workflows/docs.yml/badge.svg)](https://github.com/viniciuschiele/flask-apscheduler/actions/workflows/docs.yml)

## Features

-   Loads scheduler configuration from Flask configuration.
-   Loads job definitions from Flask configuration.
-   Allows to specify the hostname which the scheduler will run on.
-   Provides a REST API to manage the scheduled jobs.
-   Provides authentication for the REST API.
-   Integrates with [Flask
    Blueprints](https://github.com/viniciuschiele/flask-apscheduler/tree/master/examples/application_factory)

## Installation

You can install Flask-APScheduler via Python Package Index
([PyPI](https://pypi.python.org/pypi/Flask-APScheduler))

``` python
pip install Flask-APScheduler
```

## Documentation

[See Flask APSchedulers
Documentation.](https://viniciuschiele.github.io/flask-apscheduler/)

## Feedback

Please use the
[Issues](https://github.com/viniciuschiele/flask-apscheduler/issues) for
feature requests and troubleshooting usage.
