# Simple Calculator App

This is a simple calculator application built using Python's `tkinter` library. It provides basic arithmetic operations and a GUI interface for user interaction.

## Features

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

## Requirements

- Python 3.x
- tkinter library (usually comes pre-installed with Python)

## Installation and Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/golnaz76gh/simple_calculator.git
   ```

2. Navigate to the project directory:

   ```bash
   cd calculator-app
   ```

3. Run the application:

   ```bash
   python calculator.py
   ```

4. Use the GUI to perform calculations:

   - Enter numbers using the keypad buttons.
   - Perform operations by clicking on the respective operation buttons.
   - Use the 'C' button to clear the input field.

## How It Works

- The application creates a GUI window using `tkinter`.
- It defines buttons for digits (0-9), arithmetic operations, and a clear button.
- Each button is associated with a callback function that updates the input field (`Entry` widget).
- When the '=' button is pressed, the application evaluates the expression using Python's `eval()` function and displays the result.