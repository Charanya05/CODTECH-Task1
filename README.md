Name: Charanya Parasa
Company: CODTECH IT SOLUTIONS
ID: CT08DS38
Domain: Java Programming
Duration: Nov to Dec 2024
Mentor: SANTHOSH NEELA

**NOTE: OUTPUTS HAVE BEEN ADDED IN THE SEPERATE FILE**

**Overview of the SimpleCalculator Project**

The **SimpleCalculator** project is a command-line-based Java application that provides users with the ability to perform basic arithmetic operations interactively. It demonstrates the use of fundamental programming concepts like input handling, error validation, conditional logic, and arithmetic operations. 

**Objective**
The main goal of the project is to create a simple yet robust calculator that:
1. Accepts user input for numbers and operations.
2. Validates the inputs to ensure correctness.
3. Performs arithmetic calculations.
4. Provides meaningful feedback and results to the user.

**Functionalities**
1. **Arithmetic Operations**:
   - Addition
   - Subtraction
   - Multiplication
   - Division (with division-by-zero check)

2. **Input Validation**:
   - Ensures that the user inputs valid numbers and choices for operations.
   - Handles invalid inputs gracefully without terminating unexpectedly.

3. **Error Handling**:
   - Prevents crashes caused by invalid inputs such as letters or special characters.
   - Displays appropriate messages for invalid operation choices or attempts to divide by zero.

**Technical Highlights**
1. **User Input Handling**:
   - The program uses the `Scanner` class to read input from the user.
   - Numeric inputs (`num1` and `num2`) are validated using `try-catch` blocks to prevent runtime errors caused by non-numeric entries.

2. **Control Flow**:
   - Loops (`while`) ensure that invalid inputs do not break the program, allowing the user to retry until valid data is entered.
   - A `switch` statement determines which operation to perform based on the user's choice.

3. **Division by Zero**:
   - A special check prevents division by zero, which would otherwise cause a runtime exception.

4. **User-Friendly Design**:
   - Displays clear prompts and menus.
   - Outputs results in an understandable format.

**Key Java Concepts Demonstrated**
1. **Input Validation**:
   - Handles errors using exceptions and ensures user-friendly behavior.
2. **Control Structures**:
   - `while` loops for input validation.
   - `switch` statements for operation selection.
3. **Exception Handling**:
   - Uses `try-catch` to handle unexpected input gracefully.
4. **Arithmetic Operations**:
   - Demonstrates basic operations like addition, subtraction, multiplication, and division.

 **Sample Use Case**
- **User Goal**: Perform a calculation (e.g., `10 + 5`).
- **Steps**:
  1. The program asks for the first and second numbers.
  2. The user enters `10` and `5`.
  3. The program presents a menu of operations.
  4. The user selects addition (`1`).
  5. The program calculates the result (`15.0`) and displays it.

**Educational Value**
- **For Beginners**:
  - Teaches basic Java programming concepts like loops, conditional statements, and input handling.
- **For Intermediate Learners**:
  - Introduces input validation and error handling using `try-catch`.
  - Encourages thinking about edge cases (e.g., division by zero).

**Future Enhancements**
1. **Support for Advanced Operations**:
   - Add operations like modulus (`%`), exponentiation, or square root.
2. **Continuous Mode**:
   - Allow users to perform multiple calculations without restarting the program.
3. **Graphical Interface**:
   - Build a GUI-based calculator using Java Swing or JavaFX.
4. **History Tracking**:
   - Keep a record of previous calculations and allow users to review them.
