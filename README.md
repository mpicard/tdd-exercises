# TDD Exercises in Python

## Requirements

- Python >=3.7
- [Poetry](https://python-poetry.org/)

## Installation

```bash
poetry install
```

## Run tests

```bash
poetry run pytest
```

or activate the virtualenv

```bash
poetry shell
```

and run

```
pytest
```

## Exercises

### 1 - FizzBuzz

A classic exercise for beginners, one that can show the basics of TDD.

#### Requirements

1. Create a function called `fizzBuzz` that takes a number as input and returns it as a string
2. When input is a multiple of `3`, return `"Fizz"` instead of the number
3. When input is a multiple of `4`, return `"Buzz"` instead of the number
4. When input is a multple of both `3` and `4`, return `"FizzBuzz"`

### 2 - Password validation

Another classic exercise. The function should return a `True` if the password is valid and `False` otherwise as well as an error message to help the user.

#### Requirements

1. The password must be `8` characters long. If not, then the following error message should be returned `"Password must be at least 8 character"`
2. The password must contain at least `2` numbers. If not, then the following error message should be returned `"Password must contain at least 2 numbers"`
3. The password must contain at least `1` capital letter. If not, then the following error message should be returned `"Password mnust contain at least one capital letter"`
4. The password must contain at least `1` special character. If not, then the following message should be returned `"Password must contain at least one special character"`
5. The function should handle multiple validation errors. If there are multiple errors then the messages of those corresponding errors should all appear in the message.
