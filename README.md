# GitHub Actions CI/CD Pipeline Demo

## Overview
This project demonstrates a basic Continuous Integration (CI) pipeline using GitHub Actions and Python.

The workflow automatically runs unit tests whenever code is pushed to GitHub or a pull request is opened.

## Project Structure
- `app.py` - Contains addition and subtraction functions.
- `test_app.py` - Contains automated unit tests.
- `.github/workflows/python-tests.yml` - Defines the GitHub Actions workflow.
- `.gitignore` - Excludes generated files and local configuration.

## CI Workflow
1. Checks out the repository.
2. Sets up Python 3.10.
3. Runs unit tests using Python's built-in `unittest` framework.

## Run Tests Locally

Run this command:

    python3 -m unittest -v

## Expected Result
Both addition and subtraction tests should pass.

## Skills Demonstrated
- Git and GitHub
- GitHub Actions
- YAML workflow configuration
- Python
- Automated testing
- Basic CI concepts

## Cost Awareness
This project does not require AWS resources.

## Limitations
This beginner-level CI pipeline runs unit tests but does not deploy an application.