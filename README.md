# Week 4 Assignment: Hands-On Lab - Grades, Eligibility & Smart Decisions

## Files

- **welcome.py**: Contains the `welcome()` function that takes a name parameter and returns a personalized greeting message. The function is called three times with different names.

- **toolbox.py**: Contains three functions:
  - `double(number)`: Returns the input number multiplied by 2
  - `is_pass(score)`: Returns `True` if the score is 50 or more, `False` otherwise
  - `greet(name, greeting="Hello")`: Returns a greeting with an optional custom greeting parameter (defaults to "Hello")

## Reflection

The `is_pass()` function was the hardest to write at first because I kept thinking I needed to use an if statement to return True or False. However, once I realized that the comparison `score >= 50` already evaluates to a boolean value (True or False), I could simply return it directly. This made the function much simpler and cleaner.
