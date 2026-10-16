# Week 6 Assignment: Safe Functions

- `safe_tools.py`: Defines and tests `safe_divide`, `safe_number`, and `get_field` using `try/except`.
- `README.md`: Describes the assignment files and explains how invalid number input is handled.

An `if` check cannot safely catch `abc` on its own because `abc` is text that cannot be converted into an integer. Calling `int("abc")` raises a `ValueError`, so the program should use `try/except` to handle that error without crashing.
