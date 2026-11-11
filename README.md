
# Week 6 Assignment - Safe Functions

## Project Description

This project demonstrates how to use try and except in Python to handle errors safely.

## Files

- safe_tools.py: Contains three safe functions: safe_divide(), safe_number(), and get_field().
- README.md: Describes the assignment, project files, and error handling.

## Question: Why can the if check not catch abc on its own?

An if check can check conditions, but it cannot automatically catch errors that happen when converting text into an integer.

The int() function raises a ValueError when the text is "abc". Therefore, we use try and except ValueError to handle the error without crashing the program.
