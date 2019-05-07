![Build Status](https://travis-ci.com/aml-spring-19/homework-2-basilvetas.svg?token=AJqy8UpM4w9TVN6sptzA&branch=master)

# Homework 2
Base Repository for Homework 2

UNI: bsv2111

Link to travis: https://travis-ci.com/aml-spring-19/homework-2-basilvetas

## Setup

1. If you don't have Pipenv installed:
```bash
brew install pipenv
```
or
```bash
pip install pipenv
```

2. Install dependencies:
```bash
pipenv install --dev
```

3. Use Jupyter Notebook kernel in a virtualenv:
```bash
pipenv shell
python -m ipykernel install --user --name=`basename $VIRTUAL_ENV` --display-name "Homework2"
```

## Jupyter Notebook

Open notebook in virtualenv shell (make sure the Homework2 kernel is selected):
```bash
pipenv shell
jupyter notebook
```

## Testing

Run unit tests in virtualenv shell:
```bash
pipenv shell
pytest
```
