# Simple Java Calculator<br>
![cap1](https://github.com/Isuru-27/Java-Calculator/assets/139687227/71937735-0208-48b5-9a34-4ef5746b536c)

This is a simple calculator application implemented in Java using Swing for the GUI.

## Features

- Addition, subtraction, multiplication, and division operations.
- Decimal point support.
- Clear and delete functionality.
- Ability to toggle the sign of the number (positive/negative).
- Error handling for division by zero.

## How to Use

1. Run the Calculator class (`Calculator.java`) to launch the calculator application.
2. Enter numbers using the number buttons (0-9).
3. Perform arithmetic operations by clicking on the respective operation buttons (+, -, *, /).
4. Use the decimal button (.) to input decimal points.
5. Press the equal button (=) to display the result of the calculation.
6. Clear the input field by clicking the clear button (Clear).
7. Delete the last entered digit using the delete button (Delete).
8. Toggle the sign of the current number using the negative button (-).

## Bugs Fixed

- Clear Button Issue: Reset `num1`, `num2`, and `result` variables to 0 when the clear button is pressed.
- Delete Button Issue: The delete button now correctly removes the last character from the text field.
- Negative Button Issue: The negative button now properly toggles the sign of the current number.
- Division by Zero Issue: The calculator now handles division by zero gracefully, displaying an error message.

## Author

- [Isuru D Rajamanthri](#Isuru-27)


