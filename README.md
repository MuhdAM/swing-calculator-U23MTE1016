## swing-calculator-U23MTE1016

**Name:** Muhammad Aminu

**Matric NO:** U23MTE1016

**Department:** Mechatronics  

**GitHub Account:** [https://github.com/MuhdAM](https://github.com/MuhdAM)




# Swing Calculator Project

## About the Project
This project is a basic calculator application built using the **Java Swing API**. The calculator features a graphical user interface (GUI) that allows users to perform simple arithmetic operations such as addition, subtraction, multiplication, and division. The primary goal of this project is to demonstrate how Java Swing can be used to create user-friendly desktop applications.

## Features
- **Graphical User Interface (GUI)**: Built with Java Swing.
- **Basic Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Interactive Buttons**: Number buttons, operator buttons, and function buttons (clear, delete, decimal point, equals).
- **Real-time Display**: A text field to display inputs and results.

## Software Needed
To run or modify the code, ensure you have the following software installed:
- **Java Development Kit (JDK)**: Version 8 or higher.  
  [Download JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- **Integrated Development Environment (IDE)**: For example:
  - [IntelliJ IDEA](https://www.jetbrains.com/idea/)
  - [Eclipse IDE](https://www.eclipse.org/ide/)
  - [NetBeans](https://netbeans.apache.org/)
- **Git** (optional): For version control and repository management.  
  [Download Git](https://git-scm.com/)

## System Requirements
- **Operating System**: Windows, macOS, or Linux.
- **RAM**: Minimum 2GB (4GB recommended for optimal performance).
- **Storage**: Approximately 100MB of free space (for the JDK and project files).
- **Java Runtime Environment (JRE)**: Included with the JDK installation.

## How the Code Works
The calculator application is built using the Swing API and follows this structure:

1. **JFrame**:  
   The main window (`SwingCalculator`) extends `JFrame` and serves as the container for all GUI components.

2. **JTextField**:  
   A text field (`textField`) displays user input and the results of calculations.

3. **JButtons**:  
   - **Number Buttons (0-9)**: Allow users to input numbers.
   - **Function Buttons**: Include operations such as addition (`+`), subtraction (`-`), multiplication (`*`), division (`/`), decimal point (`.`), equals (`=`), delete (`DEL`), and clear (`CLR`).

4. **JPanel and Layouts**:  
   A `JPanel` with a `GridLayout` organizes the number and operator buttons into a 4x4 grid.

5. **Event Handling**:  
   The application implements `ActionListener` to handle button clicks. Depending on which button is pressed, the code updates the text field, stores the operand, or performs the calculation.

6. **Arithmetic Operations**:  
   The code captures the first number (`num1`), the selected operator, and then the second number (`num2`). When the equals (`=`) button is pressed, the application performs the calculation based on the operator and displays the result.

## How to Run the Application
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/swing-calculator-matNo.git
   cd swing-calculator-matNo
2. **Compile the Code: Open a terminal in the project directory and run**:
    ```bash
    javac SwingCalculator.java
3. **Run the Application: Execute the compiled code with**:
      ```bash
      java SwingCalculator
4. **Using an IDE**:
    Import the project into your preferred IDE.
    Run the *SwingCalculator.java* file directly.

## Challenges and Solutions
 **Challenges**:
 
1. **User Input Handling**:
  Managing multi-step inputs like "12 + 5" required separating operators and operands effectively.

2. **Division by Zero**:
  If the user attempts to divide by zero, the code could throw an exception.

**Solutions**:
  Input and operator logic were carefully implemented to avoid errors.
  Division-by-zero scenarios can be handled by displaying an error message in the *JTextField*.

## About Java Swing
Java Swing is a part of the Java Foundation Classes (JFC) and is used to build platform-independent, customizable GUI applications. Unlike AWT (Abstract Window Toolkit), Swing components are lightweight and rendered entirely in Java, which makes them flexible and consistent across different operating systems.

## Why Swing for this Project?
**Ease of Use**: Swing simplifies the creation of GUIs with its prebuilt components.
**Flexibility**: Components like JButton and JTextField can be styled and customized.
**Cross-Platform**: Applications look and behave consistently across different operating systems.

## Conclusion
This project demonstrates the basics of building a GUI-based calculator using Java Swing. It is an excellent example of handling user input, managing events, and performing arithmetic operations in a desktop application environment.
