# Ara API

Restful API for Ara, KAIST's official community service

## Getting Started

Install [pipenv](https://pipenv.pypa.io/en/latest/installation.html), a Python virtualenv management tool:

```bash
python3 -m pip install pipenv
```

Create a virtual environment (Use Python 3.12):

```bash
pipenv --python 3.12
```

Install dependencies:

```bash
pipenv shell  # Activate virtual environment
pipenv install  # Install dependencies
```

Install git hook scripts:

```bash
pre-commit install
```

## How to Run

```bash
pipenv run dev
```
