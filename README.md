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
- Initialize a Set of String values and add items to it.
- Check if a value exists in the Set.
- Remove a value from the Set.
- Print the number of values in the Set.

### Reading List:
- Understand the properties of Set and HashSet in Java.
- Learn the differences between List and Set in Java.

## Day 21 - HashMap
### Tasks:
- Initialize a HashMap with some key-value pairs.
- Retrieve a value based on its key.
- Update the value of a specific key.
- Remove a key-value pair from the HashMap.
- Print all keys and values in the HashMap.

### Reading List:
- Learn about the HashMap class and its methods.
- Understand the differences between HashMap and Hashtable.

## Day 22 - Stack
### Tasks:
- Initialize a Stack and perform basic stack operations (push, pop, peek).
- Check if the stack is empty.
- Print all elements in the stack.

### Reading List:
- Understand the Stack data structure and its usage.
- Learn the differences between Stack and other data structures like Queue and LinkedList.

## Day 23 - Queue
### Tasks:
- Initialize a Queue and perform basic queue operations (add, remove, peek).
- Check if the queue is empty.
- Print all elements in the queue.

### Reading List:
- Learn about the Queue interface and its implementations.
- Understand the differences between Queue and Stack.

## Day 24 - Object-Oriented Programming (OOP)
### Tasks:
- Create a class with attributes and methods.
- Create objects of the class and invoke their methods.

### Reading List:
- Learn about the four pillars of OOP: Encapsulation, Inheritance, Polymorphism, and Abstraction.
- Understand the benefits of OOP in software development.

## Day 25 - Simple Class
### Tasks:
- Define a simple class with attributes and methods.
- Create objects of the class and set values to the attributes.
- Print the attribute values of the objects.

### Reading List:
- Learn about classes and objects in Java.
- Understand how to define and use classes.

## Day 26 - Constructors
### Tasks:
- Define a class with different types of constructors:
  - Default constructor.
  - Parameterized constructor.
  - Copy constructor.

### Reading List:
- Learn about constructors in Java and their types.
- Understand the importance of constructors in object initialization.

## Day 27 - Inheritance
### Tasks:
- Create a base class and a derived class.
- Show how the derived class inherits attributes and methods from the base class.

### Reading List:
- Learn about inheritance in Java.
- Understand the benefits and usage of inheritance in OOP.

## Day 28 - Method Overloading
### Tasks:
- Define multiple methods with the same name but different parameters.
- Show how to call the overloaded methods.

### Reading List:
- Learn about method overloading in Java.
- Understand the benefits and use cases of method overloading.

## Day 29 - Method Overriding
### Tasks:
- Create a base class with a method.
- Create a derived class that overrides the method.

### Reading List:
- Learn about method overriding in Java.
- Understand the differences between method overloading and method overriding.

## Day 30 - Abstract Class
### Tasks:
- Define an abstract class with abstract and non-abstract methods.
- Create a subclass that extends the abstract class and implements the abstract methods.

### Reading List:
- Learn about abstract classes and methods in Java.
- Understand when and why to use abstract classes in OOP.

## Day 31 - Interface
### Tasks:
- Define an interface with multiple methods.
- Create a class that implements the interface.
- Demonstrate multiple inheritance with interfaces.

### Reading List:
- Learn about interfaces in Java and their uses.
- Understand the differences between abstract classes and interfaces.

## Day 32 - Polymorphism
### Tasks:
- Demonstrate method overloading and method overriding.
- Create a program that shows runtime and compile-time polymorphism.

### Reading List:
- Learn about polymorphism in Java.
- Understand the benefits of polymorphism in OOP.

## Day 33 - Serialization and Deserialization
### Tasks:
- Write a program to serialize an object to a file.
- Write a program to deserialize an object from a file.

### Reading List:
- Learn about serialization and deserialization in Java.
- Understand the purpose and usage of the Serializable interface.

## Day 34 - Annotations
### Tasks:
- Create custom annotations.
- Use built-in annotations like @Override, @Deprecated, and @SuppressWarnings.

### Reading List:
- Learn about annotations in Java and their uses.
- Understand the differences between custom and built-in annotations.

## Day 35 - Working with Files
### Tasks:
- Write a program to read from a file.
- Write a program to write to a file.
- Handle exceptions during file operations.

### Reading List:
- Learn about file handling in Java.
- Understand the different classes used for file operations in Java.

## Day 36 - File I/O
### Tasks:
- Write a program to read from a file using FileReader and BufferedReader.
- Write a program to write to a file using FileWriter and BufferedWriter.

### Reading List:
- Learn about FileReader, FileWriter, BufferedReader, and BufferedWriter classes.
- Understand the importance of buffering in file I/O.

## Day 37 - File I/O
### Tasks:
- Write a program to read from a file using InputStream and DataInputStream.
- Write a program to write to a file using OutputStream and DataOutputStream.

### Reading List:
- Learn about InputStream, OutputStream, DataInputStream, and DataOutputStream classes.
- Understand the differences between character and byte streams.

## Day 38 - Exception Handling
### Tasks:
- Write a program that demonstrates try, catch, and finally blocks.
- Create custom exceptions and demonstrate their usage.
- Use multiple catch blocks to handle different exceptions.

### Reading List:
- Learn about exception handling in Java.
- Understand the importance of handling exceptions in a program.

## Day 39 - Streams and Lambdas
### Tasks:
- Write a program that demonstrates the use of streams for data manipulation.
- Use lambda expressions to implement functional interfaces.

### Reading List:
- Learn about streams and their operations in Java.
- Understand the benefits of lambda expressions in functional programming.

## Day 40 - Multithreading
### Tasks:
- Create a program that demonstrates the creation of threads by extending the Thread class and implementing the Runnable interface.
- Use synchronized blocks to handle concurrency.

### Reading List:
- Learn about multithreading in Java.
- Understand the differences between extending Thread class and implementing Runnable interface.

## Day 41 - Regular Expressions
### Tasks:
- Write a program that uses regular expressions to validate user input.
- Use Pattern and Matcher classes to find and replace patterns in a string.

### Reading List:
- Learn about regular expressions in Java.
- Understand the usage of Pattern and Matcher classes.

## Day 42 - JDBC (Java Database Connectivity): Introduction
### Tasks:
- Set up a database connection using JDBC.
- Write a program to connect to a database and execute a simple query.

### Reading List:
- Learn about JDBC and its components.
- Understand the process of connecting to a database using JDBC.

## Day 43 - JDBC: CRUD Operations
### Tasks:
- Write a program to perform Create, Read, Update, and Delete operations using JDBC.

### Reading List:
- Learn about CRUD operations in JDBC.
- Understand the importance of CRUD operations in database management.

## Day 44 - JDBC: Prepared Statements and Transactions
### Tasks:
- Write a program to execute queries using prepared statements.
- Demonstrate transaction management in JDBC.

### Reading List:
- Learn about prepared statements and their advantages.
- Understand transaction management in JDBC.

## Day 45 - JDBC: ResultSet and Metadata
### Tasks:
- Write a program to read data from a ResultSet.
- Retrieve and display metadata about the database.

### Reading List:
- Learn about ResultSet and its methods.
- Understand the importance of metadata in database applications.

## Day 46 - JDBC: Advanced Concepts
### Tasks:
- Write a program to handle batch updates using JDBC.
- Use callable statements to execute stored procedures.

### Reading List:
- Learn about batch updates in JDBC.
- Understand the usage of callable statements and stored procedures.

## Day 47 - Spring Boot: Foundations
### Tasks:
- Set up a Spring Boot project.
- Create a simple Spring Boot application.

### Reading List:
- Learn about the basics of Spring Boot.
- Understand the advantages of using Spring Boot for Java applications.

## Day 48 - Spring Boot: REST API with Spring MVC
### Tasks:
- Create a REST API using Spring Boot and Spring MVC.
- Implement CRUD operations in the REST API.

### Reading List:
- Learn about Spring MVC and its components.
- Understand the process of creating RESTful web services using Spring Boot.

## Day 49 - Spring Boot: Data Persistence with JPA
### Tasks:
- Set up JPA in a Spring Boot project.
- Create entities and repositories for data persistence.

### Reading List:
- Learn about JPA and its components.
- Understand the importance of data persistence in applications.

## Day 50 - Spring Boot: CRUD Operations with Spring Data JPA
### Tasks:
- Implement CRUD operations using Spring Data JPA.
- Write tests for the CRUD operations.

### Reading List:
- Learn about Spring Data JPA and its features.
- Understand the process of testing CRUD operations in Spring Boot.

## Day 51 - Spring Boot: Advanced
### Tasks:
- Implement exception handling in a Spring Boot application.
- Secure a Spring Boot application using Spring Security.

### Reading List:
- Learn about exception handling in Spring Boot.
- Understand the basics of securing applications with Spring Security.

## Day 52 - Java Collections Framework
### Tasks:
- Explore and use different collection classes (List, Set, Map).
- Understand the differences between these collections and their use cases.

### Reading List:
- Learn about the Java Collections Framework.
- Understand the advantages of using collections in Java.

## Day 53 - LinkedList
### Tasks:
- Write a program to demonstrate the usage of LinkedList.
- Perform operations like adding, removing, and accessing elements in a LinkedList.

### Reading List:
- Learn about the LinkedList class in Java.
- Understand the differences between LinkedList and ArrayList.

## Day 54 - PriorityQueue
### Tasks:
- Write a program to demonstrate the usage of PriorityQueue.
- Perform operations like adding, removing, and accessing elements in a PriorityQueue.

### Reading List:
- Learn about the PriorityQueue class in Java.
- Understand the use cases of PriorityQueue.

## Day 55 - Deque
### Tasks:
- Write a program to demonstrate the usage of Deque.
- Perform operations like adding, removing, and accessing elements at both ends of the Deque.

### Reading List:
- Learn about the Deque interface and its implementations.
- Understand the differences between Deque and other collection types.

## Day 56 - TreeSet
### Tasks:
- Write a program to demonstrate the usage of TreeSet.
- Perform operations like adding, removing, and accessing elements in a TreeSet.

### Reading List:
- Learn about the TreeSet class in Java.
- Understand the differences between TreeSet and HashSet.

## Day 57 - TreeMap
### Tasks:
- Write a program to demonstrate the usage of TreeMap.
- Perform operations like adding, removing, and accessing elements in a TreeMap.

### Reading List:
- Learn about the TreeMap class in Java.
- Understand the differences between TreeMap and HashMap.

## Day 58 - Bit Manipulation
### Tasks:
- Write a program to demonstrate basic bit manipulation operations (AND, OR, XOR, NOT, left shift, right shift).

### Reading List:
- Learn about bit manipulation in Java.
- Understand the use cases of bit manipulation in programming.

## Day 59 - Generics
### Tasks:
- Write a program that demonstrates the use of generics.
- Create a generic class and a generic method.

### Reading List:
- Learn about generics in Java.
- Understand the benefits of using generics in programming.

## Day 60 - Collections Utility Methods
### Tasks:
- Write a program that demonstrates the usage of Collections utility methods (sort, shuffle, reverse, etc.).

### Reading List:
- Learn about the utility methods provided by the Collections class.
- Understand the use cases of these utility methods in programming.
