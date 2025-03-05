# Python Coding Guidelines

## 1. Code Style
- Follow [PEP 8](https://peps.python.org/pep-0008/) for Python coding conventions.
- Use `black` for auto-formatting and `flake8` for linting.
- Use type hints (`def func(x: int) -> str:`).

## 2. Naming Conventions
- Variables and functions: `snake_case`
- Classes: `PascalCase`
- Constants: `UPPER_CASE`

## 3. Error Handling
- Always catch exceptions explicitly.
- Use `logging` instead of `print()` for error tracking.
  
  ```python
  import logging
  logging.error("An error occurred")
