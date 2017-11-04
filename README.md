# Quadratic Equations Solver
This script is pre-commit hook for git. Before commit will send to repository it run the tests and
if tests are done the commit is ok.
# How to use
Copy pre-commit file to the next directory: ```<your-project-dir>/.git/hooks```
Then commit changes, if are there any errors in tests commit not to be done.
You get error message like this:
```bash
.....output is omitted
----------------------------------------------------------------------
Ran 4 tests in 0.001s

FAILED (errors=1)
Tests failed
```
# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
