# BSL learning Application
#### _Version 1.0.0_

#### We are creating a interactive British sign language application. This will allow users to learn the british sign language for free. Users can set up their own unique profile and track learning progress.
## Python & Django setup

* Install `python` via brew
* Clone the repo
* cd into repo
* Install `pipenv` using  `brew`

```
brew install pipenv
```

* Create a virtualenv for the project

```
pipenv --three
```

If you're having trouble completing this step, try upgrading virtualenv first
 ```
brew update pipenv
```
* Activate the virtualenv
* Activate pipenv

```
pipenv shell
```

* Install dependencies in the new virtualenv

```
pipenv install
```

* Install the pre-commit hooks

```
pre-commit install
```

```
python manage.py migrate
```

```
python manage.py runserver
```

* Server should be running at http://localhost:8000


## To run the tests

* For Django tests run:

```
python manage.py test
```
