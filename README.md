# python-part7
Learning python part 7

## VIRTUALENV

```sh
pip install virtualenv
``````

```sh
virtualenv venv --python=3.10.7
``````

To check which path is used

```sh
which python
``````

Then to change to the new path created by virtualenv

```sh
source venv/bin/activate 
``````

To  save the libs installed 

```sh
pip freeze > requirements.txt
``````

To install de libs

```sh
pip  install -r requirements.txt
``````

To stop using virtualenv


```sh
deactivate
``````

## PIPENV

To use pipenv


```sh
pip install pipenv
``````

To install the libs 

```sh
pipenv install
``````

To run the program

```sh
pipenv run python main.py
``````
