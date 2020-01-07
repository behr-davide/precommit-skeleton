# precommit-skeleton
A python pre-commit template using black, flake8, trailing whitespace, and double quote replacement hooks

Based on Lj Miranda's [article](https://ljvmiranda921.github.io/notebook/2018/06/21/precommits-using-black-and-flake8/)

# Set up 
- clone the repo
- install pipenv 
```bash
pip install -U pipenv
```
- run `pipenv install` to install dependencies listed in the Pipfile
- run `pipenv run pre-commit install` to install hooks to .git/hooks/
