# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Python Exception Handling Lab

| Title                         | Type   | Duration | Author               |
|-------------------------------|--------|----------|-----------------------
| Python Exception Handling Lab | Lesson | 1:30     | Suresh Melvin Sigera |

You are getting ready to write an interactive Python calculator in this lab.

We assume that the user input will be a formula consisting of a number, a logical operator (at least `+` and `-`), and
another number, separated by whitespace (e.g. `1 + 1`). As a first step, split the user input using `str.split()`, and
make sure that the resulting list is valid by checking:

- Raising a `FormulaError`, which is a **custom exception**, if there aren't three elements in the input.
- To convert the **first** and **third** inputs to floats, use `float_value = float(str_value)`. In the case of
  a `ValueError`
  occurring, instead of raising a `ValueError`, raise a `FormulaError` instead.
- If the second input is not `+` or `-`, again raise a `FormulaError`.

If the input is valid, perform the calculation and print out the result. The user is then prompted to provide new input,
and so on, until the **user enters quit**.

An interaction could look like this:

```text
>>> 
1 + 1
2.0
>>> 
2 + 1
3.0
>>> 
0 + 0
0.0
>>> 
quit
```

## How to submit homework

### Setup

- Step 1. Fork the repository
- Step 2. Clone your fork

### Submitting work

- Step 1. Complete your work in a file called `animals.py`
- Step 2. Push to your fork
- Step 3. Submit a pull request
- Step 3.1. Add a title (First name, Last Name) and comment

In the comment section, you must add the following:

```text
* Comfort level [0 to 5]
* Completeness [0 to 5]
* What was a win?
* What was a challenge?
* Any other comments
```