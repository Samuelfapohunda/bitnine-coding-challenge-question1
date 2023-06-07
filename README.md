# bitnine-coding-challenge-question1


This repository contains a C program that demonstrates the use of a binary tree data structure to perform mathematical calculations. The program defines various mathematical operations such as addition, subtraction, multiplication, division, absolute value, and Fibonacci sequence generation. It uses a recursive approach to evaluate the expressions provided in the binary tree structure.

**Program Overview**

The program consists of the following main components:

TypeTag enumeration: This enumeration defines different operation types, including ADD, SUB, MUL, DIV, ABS, FIB, and LIT. Each type corresponds to a specific mathematical operation.

Node structure: This structure represents a node in the binary tree. It contains the type of operation, a value (if applicable), and pointers to the left and right child nodes.

makeFunc function: This function is responsible for creating a new node with a given operation type.

makeValue function: This function creates a new node with a specified value.

fibonacci function: This function calculates the Fibonacci sequence up to a given number using dynamic programming.

calc function: This function recursively evaluates the value of a given node in the binary tree by performing the corresponding mathematical operation.

main function: The main function demonstrates the usage of the binary tree structure by creating nodes and evaluating mathematical expressions. It calculates and prints the results of various operations.



**Usage**

To compile and run the program, follow these steps:

Ensure you have a C compiler installed on your system (such as GCC).

Save the code in a file with a ".c" extension, such as "math_expression.c".

Open a terminal or command prompt and navigate to the directory where the file is saved.

Use the following command to compile the code:

gcc math_expression.c -o math_expression

After successful compilation, run the program using the following command:

./math_expression


The program will display the results of the mathematical operations calculated from the binary tree structure.
