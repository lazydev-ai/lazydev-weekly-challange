# Math Operations Python Package Challenge

## Overview

Your challenge is to implement a Python package that handles common math operations and package it as a Python wheel. The operations you need to implement are:

- **Addition**: Adds two numbers.
- **Subtraction**: Subtracts one number from another.
- **Multiplication**: Multiplies two numbers.
- **Division**: Divides one number by another. The division function should raise a `ValueError` if the divisor is zero.

## Requirements

1. **Python Version**: Use Python 3.8 or higher.

2. **Project Structure**:
   - Create a package named `math_operations`.
   - Inside this package, implement the functions in a file named `operations.py`.

3. **Package Implementation**:
   - The package should be able to handle the following operations:
     - `add(a, b)` returns the sum of `a` and `b`.
     - `subtract(a, b)` returns the difference between `a` and `b`.
     - `multiply(a, b)` returns the product of `a` and `b`.
     - `divide(a, b)` returns the quotient of `a` and `b`. Raises `ValueError` if `b` is zero.

4. **Unit Tests**:
   - Write unit tests to verify the correctness of your functions.
   - Tests should be placed in a `tests` directory.

5. **Packaging**:
   - Ensure that your package is correctly set up to be distributed as a Python wheel.
   - The package must include a `setup.py` file with the appropriate metadata.

6. **Build Command**:
   - To build your package, navigate to the root of your project and run:
     ```bash
     python setup.py sdist bdist_wheel
     ```

7. **Expected Output**:
   - A Python wheel file (`.whl`) that can be installed and used in any Python environment.
   - When installed, the package should expose the `math_operations` module with the defined functions.

## Submission

1. Implement your solution according to the above requirements.
2. Push your implementation to your fork of this repository.
3. Submit a Pull Request (PR) to this repository.

The first valid PR to pass all validation checks will be declared the winner.

## Notes

- **Challenge Duration**: This challenge is open for submission until `YYYY-MM-DD`.
- **Validation**: Your submission will be automatically validated. Ensure it meets all the requirements before submitting.
