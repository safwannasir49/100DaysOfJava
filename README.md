<h1 align="center">100 Days Of Java</h1> 

## Day 1 - Hello World
### Tasks:
1. Write a program that prints "Hello World!" to the console.
2. Add single line and multi-line comments to your code.

### Reading List:
1. Learn the difference between Java and Python.
2. What is a Java compiler and how does it work?
3. Difference between Compiler and Interpreter.

## Day 2 - Variables and Data Types
### Tasks:
1. Declare and initialize variables for various data types including integer (int), floating-point number (double), and string (String). Then, print each variable to the console.

### Reading List:
1. Learn the terms: initialization, declaration, and assignment of variables.
2. Learn the difference between Primitive and Non-Primitive data types.
3. Default values and sizes of primitive data types.

## Day 3 - Input and Output
### Tasks:
1. Write a program that reads user input and prints it to the console.
2. Modify the program to read and print different data type inputs (integers, floating-point numbers, strings).
3. Write a program to read the user input using Scanner class.

### Reading List:
1. Explore various methods for reading different types of inputs.

## Day 4 - Basic Arithmetic Operations
### Tasks:
1. Write a program that declares two integer variables and performs basic arithmetic operations (addition, subtraction, multiplication, division) on them. Print the results to the console.
2. Write a program that calculates the area of a rectangle. Prompt the user to input the length (integer) and width (integer) of the rectangle, calculate the area (length * width), and print the result.
3. Modify the above program to read decimal numbers as the length and width, and output the area to two decimal points.

### Reading List:
1. Learn about formatting options such as precision, alignment, and decimal places to present output in a clear and concise manner.

## Day 5 - Compound Assignment Operators
### Tasks:
1. Write a program that utilizes increment (++) and decrement (--) operators.
2. Write a program that utilizes the following compound operators: +=, -=, *=, /=, and %=.

## Day 6 - Type Conversion
### Tasks:
1. Write a program that performs the following tasks:
   - Convert a String to an Integer.
   - Convert a String to a Float.
   - Convert an Integer to a String using valueOf() method.
   - Convert an Integer to a String using toString() method.

## Day 7 - Math Operations
### Tasks:
1. Write a program that performs the following tasks using Math class:
   - Maximum of 2 numbers.
   - Minimum of 2 numbers.
   - Square root of a number.
   - Floor and Ceil of a float.
   - Absolute value of a double.

## Day 8 - Conditional Statements (if-else)
### Tasks:
1. Write a program that reads an integer as user input and prints whether the number is Odd or Even to the console.
2. Write a program that takes three numbers as input and prints the largest among them.
3. Write a program that checks if a given input year is a leap year or not.

## Day 9 - Switch Statement
### Tasks:
1. Write a program that reads the percentage and then prints the corresponding letter grade (A, B, C, D, or F) using switch statement.

### Reading List:
1. Understand the advantages and drawbacks of if-else and switch statements.

## Day 10 - Loops (for, while, do-while)
### Tasks:
1. Write a program that reads an input integer 'n' and prints the sum of integers from 1 to 'n' using three different types of loops: for, while, and do-while loops.
2. Write a program that reads an input integer 'n' and prints the sum of even integers from 1 to 'n' (use continue).
3. Write a program that generates random numbers between 1 and 100 until it finds a number divisible by both 5 and 7. When the number is found, print it and terminate the loop using the break statement.

## Day 11 - String Manipulation
### Tasks:
1. Write a program which performs the following tasks:
   - String Length: Calculate and print the length of a given string.
   - String Concatenation: Concatenate two strings and print the result.
   - String Comparison: Compare two strings and print whether they are equal or not.
   - String Case Conversion: Convert a given string to uppercase and lowercase and print the result.
   - String Trimming: Remove leading and trailing whitespace from a given string and print the result.
   - Substring Extraction: Extract a substring from a given string and print it.
   - String Splitting: Split a given string into substrings based on a delimiter and print the resulting substrings.
   - String Reversal: Reverse a given string and print the result.
   - String Searching: Search for a specific substring within a given string and print whether it is found or not.

## Day 12 - StringBuffer and StringBuilder
### Tasks:
1. Write a program that performs the following tasks:
   - Initialize a StringBuffer with value "Hello" and append a space and "World" and print it.
   - Initialize a StringBuilder with value "Hello" and append a space and "World" and print it.

### Reading List:
1. Learn the difference between String, StringBuffer, and StringBuilder.
2. Learn when StringBuffer and StringBuilder should be preferred over String.

## Day 13 - Arrays
### Tasks:
1. Write a program to declare and initialize an array of integers. Loop through the array and compute the average of the numbers.
2. Write a program to copy elements from one array to another array.

### Reading List:
1. Learn the difference between shallow-copy and deep-copy of arrays.
2. Learn about array index out of bounds exception.

## Day 14 - 2D-Arrays
### Tasks:
1. Write a program that performs the following tasks:
   - Initialize a 3x4 2D-Array with the values `[[23, 45, 78, 12], [56, 90, 34, 67], [89, 21, 43, 76]]`.
   - Write a function that takes a 2D array as the parameter and returns an array with the maximum value of each row. For the above example, the function should return the array `[78, 90, 89]`.
   - Write a function that takes a 2D array as the parameter and returns an array with the maximum value of each column. For the above example, the function should return the array `[89, 90, 78, 76]`.
   - Write a function that takes an nxm 2D array as a parameter and returns a mxn transformation of the input 2D array.

## Day 15 - ArrayList
### Tasks:
1. Write a program which performs the following tasks:
   - Initialize an ArrayList named `weekdays` which contains strings from Monday to Sunday.
   - Print all the elements in the ArrayList `weekdays`.
   - Sort the elements of `weekdays` alphabetically in increasing order and print them again.
   - Sort the elements of `weekdays` alphabetically in decreasing order and print them again.
   - Write a function that takes an ArrayList and a character as parameters and removes all the elements from the ArrayList that start with the given character. For example, if the parameters are `weekdays` and the character 'T', then `Tuesday` and `Thursday` should be removed from the ArrayList `weekdays`.

## Day 16 - Enums
### Tasks:
1. Write a program which performs the following tasks:
   - Initialize an enum named `weekdays` which contains strings from Monday to Sunday.
   - Print all the elements in the enum `weekdays`.

### Reading List:
1. When should you use enums in Java programming?
2. Can we remove elements from enums? And why?

## Day 17 - Date
### Tasks:
1. Write a program that performs the following tasks:
   - Initialize a date variable with the current date as value and print it.
   - Print the current epoch time.
   - Initialize a date variable with the date 7 days before the current day.
   - Compare 2 dates with `before`, `after`, and `compareTo` methods.
   - Print the current date in the following time zones: GMT, CST, IST.

## Day 18 - Functions
### Tasks:
1. Define a function (method) `isPrime` that takes an integer as a parameter and returns a boolean (true/false) whether the integer is a prime number.
2. Define a function that takes a string as a parameter and returns the number of vowels it contains.

## Day 19 - Random Number Generation
### Tasks:
1. Write a program to generate a random number.
2. Write a program to generate a random number between two integers.

### Reading List:
1. Find out why random number generation is important in programming and some common applications where it is required.

## Day 20 - Set/HashSet
### Tasks:
1. Write a program that performs the following tasks:
   - Initialize a Set of String values and add items to it.
   - Check if a value exists in the Set.
   - Remove a value from the Set.
   - Print the number of values
