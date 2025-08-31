# Calculator-using-python
**Calculator Program (Python)**

This is a simple command-line calculator built in Python. The calculator allows users to perform basic arithmetic operations such as addition, subtraction, and multiplication, with an option to exit the program.

🚀 **Features**

📋 Interactive menu display.
➕ Addition of two numbers.
➖ Subtraction of two numbers.
✖️ Multiplication of two numbers.
❌ Exit option to quit safely.
🖥️ User-friendly prompts for input.

**Project Structure**
calculator.py 

**How It Works
**
The program displays a menu of available operations.
The user selects an operation by entering its number.
The program takes two numbers as input (if required).
It performs the calculation and displays the result.
The menu is shown again until the user chooses "Exit".

**Example Run:**

Welcome to Calculator

Choose one operation:
1. Add
2. Subtract
3. multiply
4. Exit

Select the operation: 1
Let's perform addition
Give two numbers on two lines
Number 1 is: 5
Number 2 is: 7
The sum is: 12

**Functions Overview**
calculatorDisplay() → Returns the calculator menu string.
calculatorFunction(user_choice) → Executes the operation based on user input.
user_input() → Prompts the user for two numbers and returns them.
addition(a, b) → Returns the sum of a and b.
subtraction(a, b) → Returns the difference of a and b.
multiply(a, b) → Returns the product of a and b.
