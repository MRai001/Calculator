# Calculator Application

## Overview
This is a simple command-line calculator application written in Java. The application allows users to perform basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers.

## Features
- Addition of two numbers
- Subtraction of two numbers
- Multiplication of two numbers
- Division of two numbers (with validation for division by zero)
- User-friendly command-line interface

## Requirements
- Java Development Kit (JDK) 8 or higher
- Java Runtime Environment (JRE)

## How to Use
1. Compile the Java file:
   ```
   javac day3/Calculator.java
   ```

2. Run the compiled program:
   ```
   java day3.Calculator
   ```

3. Follow the on-screen prompts:
   - Enter the first number
   - Enter the second number
   - Choose an operation by entering the corresponding number:
     - 1 for Addition
     - 2 for Subtraction
     - 3 for Multiplication
     - 4 for Division

4. The result will be displayed on the screen.

## Example
```
Enter the first number
10
Enter the second number
5
Choose an operation
1. Addition
2. Subtraction
3. Multiplication
4. Division
3
Result: 50.0
```

## Code Structure
The application consists of a single Java class `Calculator` in the `day3` package. It uses `Scanner` to get user input and performs arithmetic operations based on the user's choice.

## Error Handling
The application includes basic error handling:
- Validates division by zero
- Checks for invalid operation choices

## License
[Your License Here] - Feel free to modify and distribute this code as needed.
