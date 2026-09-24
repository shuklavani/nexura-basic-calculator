# NEXURA Basic Calculator

A simple command-line calculator developed in C++ for the NEXURA Tech Team Recruitment Round 1 task.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Division-by-zero error handling
- Invalid operation handling

## Technologies Used

- C++
- Standard Input/Output (`iostream`)

## How to Run

1. Clone or download this repository.
2. Compile the program using a C++ compiler.
3. Run the generated executable.
4. Enter two numbers and select an arithmetic operation.

## Sample Output

### Addition

```text
===== Basic Calculator =====
Enter first number: 25
Enter second number: 5

Choose an operation (+, -, *, /): +
Result: 30
```

### Subtraction

```text
===== Basic Calculator =====
Enter first number: 25
Enter second number: 5

Choose an operation (+, -, *, /): -
Result: 20
```

### Multiplication

```text
===== Basic Calculator =====
Enter first number: 25
Enter second number: 5

Choose an operation (+, -, *, /): *
Result: 125
```

### Division

```text
===== Basic Calculator =====
Enter first number: 25
Enter second number: 5

Choose an operation (+, -, *, /): /
Result: 5
```

### Division by Zero

```text
===== Basic Calculator =====
Enter first number: 10
Enter second number: 0

Choose an operation (+, -, *, /): /
Error: Division by zero is not allowed.
```

## Implementation

The program uses a `switch` statement to perform the selected arithmetic operation. Before division, the program checks whether the second number is zero to prevent division by zero.

## Error Handling

The program displays an error message when:

- The user attempts to divide by zero.
- The user enters an invalid operation.

## NEXURA Recruitment Task

This project was created for the NEXURA Tech Team Recruitment Round 1 - Language Task 1: Basic Calculator.
