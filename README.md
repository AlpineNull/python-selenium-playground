# Python Selenium Playground

A small practice project for learning browser automation with Python and Selenium.

The repository contains automated tests for selected examples from
[The Internet](https://the-internet.herokuapp.com/).

## Tech stack

- Python
- Selenium WebDriver
- unittest
- requests

## Installation

Install the dependencies:

```powershell
python -m pip install -r requirements.txt
```

## Running the tests

Run all tests:

```powershell
python -m unittest tests -v
```

Run a single test:

```powershell
python -m unittest tests.TestCasesTheInternetHerokuapp.test_checkboxes -v
```

## Notes

This is a practice project used for learning and experimenting with Selenium and Python.

Some tests depend on the current behavior of the external test website and may fail if the website is unavailable or changes.