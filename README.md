# 🧮 Calculator with Tests

This is a simple Python-based calculator project that supports a variety of mathematical operations.  
It includes **unit tests** to ensure each function works as expected.

## 📦 Features

The calculator provides the following operations:

- **Addition**  
  `add(x, y)` → Returns the sum of `x` and `y`.  
  Example: `add(2, 3)` → `5`

- **Subtraction**  
  `subtract(x, y)` → Returns the difference between `x` and `y`.  
  Example: `subtract(7, 4)` → `3`

- **Multiplication**  
  `multiply(x, y)` → Returns the product of `x` and `y`.  
  Example: `multiply(3, 4)` → `12`

- **Division**  
  `divide(x, y)` → Returns the result of dividing `x` by `y`.  
  Handles division by zero with an appropriate error message.  
  Example: `divide(8, 2)` → `4`

- **Square**  
  `square(x)` → Returns the square of `x`.  
  Example: `square(3)` → `9`

- **Square Root**  
  `sqrt(x)` → Returns the square root of `x`.  
  Handles negative input with an error message.  
  Example: `sqrt(9)` → `3`

- **Power**  
  `power(x, y)` → Returns `x` raised to the power of `y`.  
  Example: `power(2, 3)` → `8`

## ✅ Testing

The script includes built-in unit tests for each function:

- Tests are run automatically when executing the file.
- Covers correct results and edge cases (e.g., division by zero, negative square roots).
- Example output when running the script:

