# cookiecutter_poetry_django

python django project template with pre-configured development tools:
 - mypy: Static Typing for Python
 - poetry: Dependency Management for Python
 - flakehell: flake8 wrapper (Tool For Style Guide Enforcement)
 - useful pre-configured Flake8 plugins:
   - flake8-docstrings: docstring style checker
   - flake8-commas: enforce better comma placement
   - flake8-quotes: lint for quotes
   - flake8-bandit: security testing built right into your workflow
   - flake8-bugbear: finding likely bugs and design problems in your program
   - flake8-builtins:Check for python builtins being used as variables or parameters
   - flake8-comprehensions: write better list/set/dict comprehensions
   - flake8-eradicate: find commented out (or so called "dead") code
   - flake8-isort: check if the imports on your python files are sorted the way you expect
   - flake8-mutable: check mutable default argument
   - pep8-naming: Check your code against PEP 8 naming conventions
   - django-stub
   - django-environ
 - black: Code Formatter
 - tox: automation tool with preconfigured test script (tox.ini)
 - pytest
 
## usage
 1. install cookiecutter: 
 `pip install --user cookiecutter` [link](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html)
 2. install poetry: 
 `curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -`
 [link](https://python-poetry.org/docs/)
 3. create project: `cookiecutter gh:hamedsh/cookiecutter-poetry-base`
