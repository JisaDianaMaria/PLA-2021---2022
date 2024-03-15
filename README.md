# PLA-2021-2022
Assembly language project.
Pocket calculator application in base 16.

Requirements:
Develop a program that executes the functions of a pocket calculator with arithmetic and logical operations (with 32-bit integers) in hexadecimal. The operations must be implemented as functions.
Requested operations: +, -, *, /.
The user will input expressions from the keyboard that they want to calculate. The "=" sign means that the expression should be calculated, and the result displayed on the screen. If the expression starts with an operator, the first operand is considered to be equal to the last result obtained. If no result has been calculated previously, the operand is considered to be 0. The program will recognize the "exit" command (terminating the program). Until the "exit" command is received, the program will run continuously.
An expression can contain any number of operands. Multiplication and division take precedence.

Example:
>Enter an expression:
>2+3-2*2=1
>Enter an expression:
>+0A=0B
>Enter an expression:
>exit

