**Calculator Project**

This is a simple Python-based calculator project that supports basic mathematical operations. The project includes functions to perform addition, subtraction, multiplication, division, and more advanced operations like power, square, and square root. It also includes unit tests to verify the correctness of each function.

Features
The calculator supports the following operations:

Addition: add(x, y)
Returns the sum of x and y.
Example: add(2, 3) => 5

Subtraction: subtract(x, y)
Returns the difference of x and y.
Example: subtract(7, 4) => 3

Multiplication: multiply(x, y)
Returns the product of x and y.
Example: multiply(3, 4) => 12

Division: divide(x, y)
Returns the division of x by y.
Handles division by zero with an appropriate error message.
Example: divide(8, 2) => 4

Square: square(x)
Returns the square of x.
Example: square(3) => 9

Square Root: sqrt(x)
Returns the square root of x.
Handles negative numbers with an error message.
Example: sqrt(9) => 3

Power: power(x, y)
Returns x raised to the power of y.
Example: power(2, 3) => 8


Testing
Unit tests are included for each function to ensure correctness. The tests validate:

Correct outputs for valid inputs.
Proper error handling for invalid inputs (e.g., division by zero, square root of negative numbers).
