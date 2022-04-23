## Git Hooks - A collection of git-hook configurations & pre-commit reference


### Primary references
 - https://pre-commit.com/
 - https://github.com/pre-commit/pre-commit-hooks
 - https://githooks.com/

### Installation
1. Copy `.pre-commit-config.yaml`, `pyproject.toml` & `setup.cfg` templates
2. `pre-commit` installation instructions
  with Pipenv:
    - `pipenv install pre-commit~=2.18.1 --dev`
    - `pipenv install black~=22.3.0 --dev`
    - `pipenv install flake8~=4.0.1 --dev`
    - `pipenv install isort~=5.10.1 --dev`
  with Poetry:
    - `poetry add -D pre-commit@^2.18.1`
    - `poetry add -D black@^22.3.0`
    - `poetry add -D flake8@^4.0.1`
    - `poetry add -D isort@^5.10.1`
3. Edit `pyproject.yaml` for project specific details for `black` & `isort`
4. Edit `setup.cfg` for project specific details for `flake8`
5. `pre-commit install`
6. `pre-commit run --all-files`
7. Make fixes and exceptions where appropriate
8. Continue with normal workflow

---
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/kevinbowen777/git-hooks/-/blob/master/LICENSE)
---
### Reporting Bugs

   Visit the [Issues page](https://github.com/kevinbowen777/git-hooks/issues)
      to view currently open bug reports or open a new issue.
