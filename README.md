# python-dev-template

This is a simple template repository that serves as a "quick start" for Python projects.

It includes configurations for `poetry` and a few development dependencies to be used as `pre-commit` hooks:

 * [black](https://github.com/psf/black)
 * [ruff](https://github.com/astral-sh/ruff) (using the pre-commit version [here](https://github.com/charliermarsh/ruff-pre-commit))
 * [mypy](https://github.com/python/mypy) (using the pre-commit version [here](https://github.com/pre-commit/mirrors-mypy))


Usage
---

To get started using this template, create a `poetry` virtual environment and install `pre-commit` hooks:

```bash
> poetry install && pre-commit install
```
