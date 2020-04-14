[![Tests](https://github.com/ankcorp/proxywars/workflows/Tests/badge.svg)](https://github.com/ankcorp/proxywars/actions?workflow=Tests)
[![codecov](https://codecov.io/gh/AnkCorp/proxywars/branch/master/graph/badge.svg)](https://codecov.io/gh/AnkCorp/proxywars)

# Proxy Wars

Benchmarking reverse proxy servers

## Getting Started

### Requirements

- Docker
- Docker-Compose

## Contrubuting

### Create a python virtual env

```bash
python -m venv venv     # create python environment
. ./venv/bin/activate    # activate python enviroment
```

### Install poetry

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
```
or

```bash
pipx install poetry
```

### Install nox

```bash
pip install nox
```
### Nox

Run tests, lint check, type check, doc tests, coverage
```bash
nox
```
