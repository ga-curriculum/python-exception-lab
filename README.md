# <picture><img src="https://ga-curriculum.github.io/universal-resources-internal/ga-logos/ga-red-cog-128x128.png" alt="" height="48" align="absmiddle"></picture> Python Exception Handling Lab

| Title                         | Type   | Duration | Author               |
|-------------------------------|--------|----------|-----------------------
| Python Exception Handling     | Lab    | 2:00     | Suresh Melvin Sigera |

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

<hr>

Write a program that calculates and prints the value according to the given formula:
`Q = Square root of [(2 * C * D)/H]`
Following are the fixed values of `C` and `H`:

`C is 50. H is 30`.

`D` is the variable whose values should be input to your program in a comma-separated sequence.

Example

Let us assume the following comma separated input sequence is given to the program:
`100,150,180`

The output of the program should be:
`18,22,24`


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
