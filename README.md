# Conditional-Statements-using-python-in-internship-3
# Documentation: Conditional Statements in Python

## Objective

This program demonstrates the use of Python conditional statements:

* `if`
* `elif`
* `else`

These statements allow a program to make decisions based on specified conditions.

## Program Code

```python
age = 18

if age > 18:
    print("you can vote")
elif age == 18:
    print("you can vote equally")
else:
    print("always")
```

## Explanation

### 1. Variable Declaration

```python
age = 18
```

* A variable named `age` is initialized with the value `18`.

### 2. `if` Statement

```python
if age > 18:
    print("you can vote")
```

* Checks whether `age` is greater than `18`.
* If the condition is `True`, the message `"you can vote"` is printed.

### 3. `elif` Statement

```python
elif age == 18:
    print("you can vote equally")
```

* If the first condition is `False`, Python checks whether `age` is exactly `18`.
* If this condition is `True`, the message `"you can vote equally"` is printed.

### 4. `else` Statement

```python
else:
    print("always")
```

* Executes when none of the previous conditions are `True`.
* In this example, it prints `"always"`.

## Sample Output

Given:

```python
age = 18
```

The output is:

```
you can vote equally
```

## Important Note

The original code used:

```python
print(always)
```

This causes a `NameError` because `always` is treated as a variable that has not been defined. To print the word itself, it must be enclosed in quotation marks:

```python
print("always")
```

## Key Concepts Used

* `if` – Executes code when a condition is `True`.
* `elif` – Tests another condition if the previous one is `False`.
* `else` – Executes when all preceding conditions are `False`.
* Comparison operators:

  * `>` : Greater than
  * `==` : Equal to

## Conclusion

Conditional statements enable Python programs to make decisions based on different conditions. They are essential for implementing logic such as eligibility checks, grading systems, menu-driven programs, and many other real-world applications.
