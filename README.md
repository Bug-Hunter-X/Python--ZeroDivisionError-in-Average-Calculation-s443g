# Python: ZeroDivisionError in Average Calculation

This repository demonstrates a common Python error: `ZeroDivisionError`. The `calculate_average` function in `bug.py` fails when given an empty list as input. The corrected version in `bugSolution.py` adds a check to prevent this error.

## Bug Description
The original code attempts to calculate the average of a list of numbers without checking for an empty list. When an empty list is passed, `len(numbers)` becomes zero, resulting in division by zero and a `ZeroDivisionError`. 

## Solution
The improved code first checks if the input list is empty. If it is, it returns 0, preventing the division by zero. Otherwise, it proceeds with the average calculation.  This ensures robust error handling.