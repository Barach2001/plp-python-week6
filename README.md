# Week 6 Assignment: Safe Functions

- `safe_tools.py`: Defines and tests three functions that safely handle division by zero, invalid whole-number input, and missing dictionary keys.
- `README.md`: Describes the assignment files and explains why exception handling is needed for invalid input.

**Why can the if check not catch `abc` on its own?**

The problem happens when Python tries to convert the text `"abc"` into an integer using `int()`. That conversion raises a `ValueError`, so the program uses `try/except` to catch the specific error and return a helpful message instead of crashing.
