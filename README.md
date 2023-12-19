# Python REST API Learning Project

## Overview

Welcome to the Python REST API Learning Project! This project is designed to help you learn and practice building a RESTful API using Django and FastApi, both are popular web frameworks.

## Prerequisites

To complete this project, you will need to have the following installed on your computer:

- [Python 3.6.1](https://www.python.org/downloads/)


## Getting Started

To get started, you will need to clone this repository to your local machine:

```bash
git clone git@github.com:Alejandro-86/rest_api_python.git
```

Next, you will need to install the dependencies:

```bash
poetry install
```

Once the dependencies are installed, you can run the application:
### Django backend

For the Django backend you can do it with the following command:

```bash
poetry run python django/countryapi/manage.py runserver
```

you can test the endpoints with the following command:

```bash
curl -i http://127.0.0.1:8000/countries/ -w '\n'
```

You can close the server with the following command:

```bash
CTRL + C
```

### FastApi backend

For the FastApi backend you can do it with the following command:

```bash
cd fastapi
poetry run uvicorn app:app --reload
```

You can test the endpoints with the following command:

```bash
curl -i http://127.0.0.1:8000/countries -w '\n'
```

Close the server with the following command:

```bash
CTRL + C
```
