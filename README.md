# Python CLI Calculator

A simple command-line calculator written in Python, with calculation history and input validation.

## Features

- Add, subtract, multiply, and divide
- Calculate a percentage of a total, square a number, and find a square root
- View and clear calculation history
- Validate input and report errors for division by zero, negative square roots, and results that are too large

## Requirements

Python 3.8 or newer. No extra packages needed.

## How to run

```bash
python calculator.py
```

## Example session

```text
=== Calculator ===
+     add            -     subtract
*     multiply       /     divide
%     percent of a total
sq    square         sqrt  square root
h     show history   c     clear history
m     show menu      q     quit

Enter your choice: +
Enter number 1: 5
Enter number 2: 3
8.0

Enter your choice: /
Enter number 1: 5
Enter number 2: 0
Error: Cannot divide by zero.

Enter your choice: q
Goodbye!
```

## What I learned

Functions, dictionaries, loops, exceptions (`raise` and `try/except`), and input validation.
