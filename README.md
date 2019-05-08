# Sparkify Project

## Table of Contents

- [Sparkify Project](#sparkify-project)
  - [Table of Contents](#table-of-contents)
  - [Project Definition](#project-definition)
  - [Dependencies](#dependencies)
  - [Installation](#installation)
  - [Instructions](#instructions)
    - [Jupyter Notebook](#jupyter-notebook)
    - [Web Application](#web-application)
  - [Project Organization](#project-organization)
  - [Analysis](#analysis)
  - [Conclusion](#conclusion)

## Project Definition

This is a [Udacity nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) project (Data Science Capstone).
This project uses users' event data from Sparkify, which is an imaninary digital music service similar to Spotify or Pandora, to build a model for an API that predicts chrn, and deploy a Flask based web app.

## Dependencies

- Python3.7
- [Poetry](https://github.com/sdispater/poetry)

## Installation

```bash
cd sparkify-project
poetry install
```

## Instructions

### Jupyter Notebook

```bash
cd sparkify-project
poetry run jupyter notebook
```

### Web Application

```bash
cd sparkify-project
poetry run python run.py
```

Go to `http://0.0.0.0:3001/`

## Project Organization

```text
[project root]
├── app
│   ├── run.py
│   └── templates
│       └── *.html
├── data
│   ├── *.py
│   └── mini_sparkify_event_data.json
├── models
│   └── *.py
├── notebooks
│   └── *.ipynb
├── README.md
├── .gitignore
├── poetry.lock
└── pyproject.toml <- config file contains the project information and package dependencies etc.
```

## Analysis

TODO: not yet written

## Conclusion

TODO: not yet written
