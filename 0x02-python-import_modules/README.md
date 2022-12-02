Write a program that imports all functions from the file calculator_1.py and handles basic operations.



Usage: ./100-my_calculator.py a operator b

If the number of arguments is not 3, your program has to:

print Usage: ./100-my_calculator.py <a> <operator> <b> followed with a new line

exit with the value 1

operator can be:

+ for addition

- for subtraction

* for multiplication

/ for division

If the operator is not one of the above:

print Unknown operator. Available operators: +, -, * and / followed with a new line

exit with the value 1

You can cast a and b into integers by using int() (you can assume that all arguments will be castable into integers)

The result should be printed like this: <a> <operator> <b> = <result>, followed by a new line

You are not allowed to use * for importing or __import__

Your code should not be executed when imported
