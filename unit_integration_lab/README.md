# Lab-09: Unit & Integration Testing

## Student Information
- Name: Rahmeen
- Roll Number: 231400061

## Project Description
This project demonstrates unit testing and integration testing using pytest.
A simple banking application is tested to ensure individual functions and
combined workflows behave correctly.

## How to Run Tests
1. Install dependencies:
   pip install -r requirements.txt

2. Run all tests:
   pytest

3. Run with verbose output:
   pytest -v

4. Run specific file:
   pytest test_unit.py

5. Generate HTML report:
   pip install pytest-html
   pytest --html=report.html -v

## GitHub Actions
GitHub Actions is configured to automatically run unit and integration tests
on every push and pull request using Python and pytest.
