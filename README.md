This Python script is a scientific calculator GUI application built using the ttkbootstrap library, which provides a modern and visually appealing interface. Here's a breakdown of its features and functionality:

........Key Features.......
   
GUI Elements:

1 - The calculator has a responsive and resizable grid layout.
A large entry widget displays the current expression or result.
Buttons are designed dynamically with modern styles using ttkbootstrap.
Basic Operations:

2- Standard arithmetic operations (+, -, *, /, %).
Parentheses for complex expressions.
Scientific Functions:

3- Trigonometric functions (sin, cos, tan).
Logarithmic functions (log, ln).
Square, square root, reciprocal, and exponential functions.
Special constants like π and e.
Memory Operations:

4- Store (M+, M-), recall (MR), and clear (MC) memory values.
Error Handling:

5- Displays "Invalid Expression" or "Error" for incorrect input or calculations.
Interactive Controls:

6- Clear (C) resets the calculator.
Backspace (⌫) deletes the last character.
Dynamic Button Layout:

Buttons are added programmatically to simplify design and ensure scalability.
The "0" button spans two columns, and the "=" button spans two columns for usability.
Technical Details
The application uses eval for evaluating mathematical expressions.
Special functions like trigonometry and logarithms use the math module.
Memory operations use a global variable to store values.
Responsive layout is achieved by configuring grid weights, making buttons resizeable.
Usage
The calculator is well-suited for basic and advanced calculations, offering both usability and aesthetic appeal with the "darkly" theme provided by ttkbootstrap.
