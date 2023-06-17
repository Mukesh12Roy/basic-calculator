# basic-calculator

# This program is a simple calculator application built using the Vite framework and React. 
    It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

The program utilizes the useReducer hook from React to manage the state of the calculator. The state consists of currentOperand, previousOperand, and operation, which keep track of the numbers entered by the user and the selected operation.

The program defines a set of action types in the ACTIONS object, which include adding a digit, choosing an operation, clearing the calculator, deleting a digit, and evaluating the expression.

The reducer function is responsible for updating the state based on the dispatched actions. It handles actions like adding digits, choosing operations, clearing the calculator, deleting digits, and evaluating the expression. The evaluate function is used to perform the actual computation based on the selected operation.

The formatOperand function is a helper function that formats the operands to display them properly in the calculator's output.

The App component is the main component of the program. It renders the calculator's UI, including the output display and buttons for digits, operations, and control actions. Each button dispatches the corresponding action when clicked.

Overall, this program provides a basic calculator interface and logic for performing arithmetic calculations. It demonstrates the use of React's useReducer hook for managing state and showcases how to build a simple application using Vite and React.
