# Python Template
Re-useable entrypoint for Python projects

# Features
- Pre-Commit for code formatting and linting
- PyTest integration
- Typing with mypy

# Usage

## Dependencies
Install [Poetry](https://python-poetry.org/)
```bash
pip install poetry
```

Install initial project dependencies
```bash
poetry install
```

Initialize pre-commit
```bash
poetry shell
pre-commit install
# Optional
pre-commit run --all-files
```
