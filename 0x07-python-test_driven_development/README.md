0x07-python-test driven development
Function Examples
This repository provides examples of Python functions with corresponding test cases. Each function is implemented in a separate module and has associated tests written using the doctest module.

Functions
Add Integer: A function that adds two integers and returns the result.
Divide Matrix: A function that divides each element of a matrix by a given divisor and returns a new matrix.
Divide Matrix (Improved): An improved version of the matrix division function with additional validation and error handling.
Say My Name: A function that prints a person's name.
Print Square: A function that prints a square of '#' characters.
text indentation: A function that prints a text with 2 new lines after each of these characters '.',' ?',and ':'.".
Test Cases
Test cases for each function are provided in separate text files in the tests directory. The test cases cover various scenarios to ensure the functions work correctly and handle different input cases.

Running Tests
To run the tests for a specific function, you can use the python3 -m doctest -v command followed by the path to the test file. For example:

python3 -m doctest -v ./tests/3-say_my_name.txt | tail -2
