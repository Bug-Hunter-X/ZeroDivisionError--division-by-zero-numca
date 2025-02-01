# ZeroDivisionError: division by zero
This repository demonstrates a common Python error: `ZeroDivisionError`.  The code attempts to divide by zero, which is undefined and causes the program to crash.

## Bug Description:
The function `my_function` attempts to return the result of `a / b`. However, when `b` is 0, a `ZeroDivisionError` is raised.

## Solution:
The solution involves adding error handling to gracefully handle cases where `b` is zero, preventing the program from crashing. This can be done using a `try-except` block.
