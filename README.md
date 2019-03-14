Installing required dependencies:

- pip install -e .
  - you may want to be in a virtual environment if you don't want to install flask globally

Installing Developer Dependencies:

- pip install -e '.[test]'
  - this will install pytest and coverage so you can test

Starting flask:

- FLASK_APP=flask_boilerplate
- FLASK_ENV=development
- flask run
