# Simple Calculator
A basic web-based calculator that supports two input modes:
- **INFIX** notation (standard arithmetic expressions like `3 + 4`)
- **RPN** (Reverse Polish Notation) mode

This calculator allows you to perform addition, subtraction, multiplication, and division with a clean and user-friendly interface.

## Features
- Toggle between INFIX and RPN input modes
- Numeric input buttons (0–9) and decimal point
- Basic arithmetic operators: `+`, `-`, `*`, `/`
- Clear button to reset the calculator
- Simple display field showing current input or result

## How to Use
1. Open `Calculator.html` in a web browser.
2. Choose the input mode by selecting either the **INFIX** or **RPN** radio button.
3. Click on the numeric buttons and operators to build your calculation.
4. Press `=` to compute the result.
5. Press `C` to clear the input and start over.

*Note: This calculator currently does not have error handling for invalid input sequences.*

## Technologies Used
- HTML for the layout and user interface
- CSS for styling and visual design
- JavaScript for calculator logic and interactions

## Project Structure
- `Calculator.html` — main HTML file containing the calculator UI and embedded JavaScript logic
- `Calculator.css` — CSS styles for the calculator's appearance

## Limitations & Notes
- The calculator processes integers only (no floating-point arithmetic support yet).
- No advanced error handling (invalid sequences may produce unexpected results).
- RPN mode requires operator and operand inputs in the correct order to work properly.
- Future improvements could include support for decimals, parentheses, and improved input validation.

## Run Locally
Simply clone the repository and open `Calculator.html` in any modern web browser:
```
git clone https://github.com/mginham/simple-calculator.git
cd simple-calculator
```
Open Calculator.html in your browser.
