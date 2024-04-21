# sortie-pre-commit

[![PyPI version](https://badge.fury.io/py/sortie.svg)](https://badge.fury.io/py/sortie)

A [pre-commit](https://pre-commit.com/) hook for [Sortie](https://pypi.org/project/sortie/).

Sortie is an opinionated tool for formatting your `pyproject.toml` files. 

Distributed as a standalone repository to enable installing Sortie via prebuilt wheels from PyPI.

# Using Sortie with pre-commit

To use Sortie (v0.1.0) via pre-commit, add the following to your `.pre-commit-config.yaml`:

```yaml
  - repo: https://github.com/8bit-pixies/sortie-pre-commit
    rev: v0.1.0
    hooks:
      - id: sortie
```



