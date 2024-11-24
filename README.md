# CODETECH-task-1

Name:Salim Ramjan Pinjari
Id:CT4MTJPO1
Domain:Java Programming 
Duration: July 20th To November 20th 2024
Mentor:Muzammil Ahamad.

My Task is to create the Calculator , which calculates basic Operation This task meets all of the requirements and has been thoroughly tested.

1. Set Up Your Development Environment
Ensure you have the Java Development Kit (JDK) installed.
Set up a project in an IDE like IntelliJ IDEA, Eclipse, or NetBeans to work with Swing.

3. Design the User Interface (UI)
Frame (JFrame): This is the main container where all components will reside.
Buttons (JButton): You will need buttons for digits (0-9), arithmetic operators (+, -, *, /), a decimal point, clear (C), and equals (=).
Text Field (JTextField): A text field will be used to display the input and result.
Layout: Organize the buttons in a grid layout (GridLayout) to make the calculator easy to use.

5. Create the Basic Layout
Create a JFrame window with a title like "Calculator".
Add a JTextField at the top for displaying calculations.
Use a JPanel with GridLayout to arrange buttons for digits and operators in a grid.

7. Define Calculator Logic
Variables for Operation: You will need variables to keep track of the current number, the operator, and the result.
Event Handling: Attach listeners to each button so that when a button is clicked, the corresponding action (e.g., number, operator, or clear) is performed.
Perform Calculations: When the "=" button is pressed, evaluate the expression and display the result in the text field.
9. Event Handlers for Buttons
   
Digit Buttons (0-9): Append the clicked digit to the display.
Operator Buttons (+, -, *, /): Store the operator and the current number, then clear the display for the next input.
Equal Button (=): Perform the calculation based on the entered numbers and operator, and display the result.
Clear Button (C): Clear the display and reset the calculation state.
Decimal Point (.): Append a decimal point to the current number.

11. Implement Calculation Logic
You can implement simple arithmetic operations by writing methods that take two operands and an operator.
Consider using a switch statement to handle the different operators, or you can use a more complex expression evaluation approach.

Snapshot:

![Calculator output1](https://github.com/user-attachments/assets/0c446a8d-b0de-49a3-a5de-f1cf39fa3a58)
