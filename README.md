# Math Interpreter 🧮

A simple Python program that evaluates basic mathematical expressions entered by the user.

## About the Project
The program asks the user to enter a mathematical expression in the format:

```text id="x3q7mt"
x y z
```

where:

* `x` is an integer
* `y` is one of `+`, `-`, `*`, or `/`
* `z` is an integer

The program evaluates the expression and prints the result as a floating-point number with one decimal place.

For example:

```text id="f9r5k2"
1 + 1 → 2.0
2 - 3 → -1.0
2 * 2 → 4.0
50 / 5 → 10.0
```

## How It Works

The program receives the expression as a string and uses `split()` to separate the numbers and operator.

For example:

```python
x, y, z = expression.split(" ")
```

The numbers are then converted to integers and the appropriate mathematical operation is performed based on the operator.

For division, the program assumes that `z` is not `0`.

## What I Practiced

* `input()`
* Working with strings
* `split()`
* Multiple assignment
* Converting strings to integers
* Arithmetic operators
* `if / elif / else`
* Floating-point numbers
* Formatting numbers to one decimal place

## Technologies

* Python

## Course

This project was completed as part of **CS50's Introduction to Programming with Python** by Harvard University.
