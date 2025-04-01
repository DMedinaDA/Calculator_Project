# Calculator_Project

This Python project is a simple yet versatile calculator program that performs basic arithmetic operations: addition, subtraction, multiplication, and division. The program allows users to input two numbers and choose an operation interactively. It features a user-friendly interface and supports multiple calculation attempts in a single session.
Features
Basic Arithmetic Operations:

Addition

Subtraction

Multiplication

Division

Interactive User Input:

Users can input numbers and select operations dynamically.

Supports various ways to specify operations (e.g., "A", "Add", "Addition").

Error Handling:

Ensures users input valid choices for operations.

Allows users to exit gracefully after completing calculations.

Repeat Calculations:

Users can perform multiple calculations in one session by choosing whether to continue or exit.

How It Works
User Input:

The program prompts the user to enter two numbers.

The user selects an operation by typing its corresponding letter or name (e.g., "A" for addition, "S" for subtraction).

Operation Execution:

Based on the user's choice, the program calls the appropriate function (add, subtract, multiply, or divide) to compute the result.

Output:

The result of the calculation is displayed in a clear format (e.g., Result: 5 + 3 = 8).

Loop for Multiple Calculations:

Users can perform additional calculations by responding "yes" or "no" when prompted.

Code Breakdown
Functions
add(x, y): Returns the sum of x and y.

subtract(x, y): Returns the difference between x and y.

multiply(x, y): Returns the product of x and y.

divide(x, y): Returns the quotient of x divided by y.

Main Logic
The program uses a while True loop to keep asking the user for inputs until they decide to exit.

It validates user choices using conditional statements (if-elif-else) and ensures proper handling of invalid inputs.

Results are displayed in an easy-to-read format.
