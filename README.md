# Formatters + Hooks: autopep8, pylint, and pre-commit

This repository provides a quick PoC to automate code linting before we are
able to commit Python code to git.

## Tools

* [autopep8](https://github.com/hhatto/autopep8): a code simple formatter
* [pylint](https://github.com/PyCQA/pylint): a great linter
* [pre-commit](https://github.com/pre-commit/pre-commit): a project that makes it easy to run the above tools pre-commit

## Setup

```bash
make setup
```

Feel free to read the Makefile contents to get a feeling for what's happening.

## Usage

1. Try to make the Python code in main.py poorly-formatted
2. Commit the poorly-formatted code
3. Squirm

## Author

Samuel Roeca *samuel.roeca@gmail.com*
