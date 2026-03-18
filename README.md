# `Chris Python data science and AI Copier template`

A Copier template for Python data science and AI projects.

This template was originally based off [govcookiecutter](https://github.com/best-practice-and-impact/govcookiecutter).

## Getting started

Create a new directory for your project, then navigate to it. Assuming you have already [installed copier](https://copier.readthedocs.io/en/stable/), just run:

```shell
copier copy https://github.com/chrishylanduk/data-science-copier.git .
```

Once you've answered all the prompts, your project will be created.

## Setting up your new project

After creating your project, set up the development environment:

```shell
uv sync --group dev
uv run pre-commit install
```

This will install dependencies and set up pre-commit hooks for code quality checks.
