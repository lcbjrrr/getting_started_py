 
**Chapter 4: Functions in Python**

**Introduction**

This chapter introduces functions, a fundamental building block of programming. Functions allow you to organize your code into reusable blocks, making it more modular, readable, and efficient.

**Chapter Objectives**

* Understand the purpose and benefits of using functions.
   
* Learn how to define and call functions in Python.
   
* Explore function parameters, return values, and scope.
   
* Implement recursive functions.

**Defining and Calling Functions**

In Python, you define a function using the `def` keyword, followed by the function name, parentheses `()`, and a colon `:`. The code block within the function is indented. To execute a function, you "call" it by its name followed by parentheses.

```python
def greet():
    print("Hello!")

greet()  # Calling the function
```

**Function Parameters**

Functions can take input values called parameters. These are specified within the parentheses during the function definition.

```python
def greet_user(name):
    print("Hello, " + name + "!")

greet_user("Alice")
```

**Return Values**

Functions can also return values using the `return` statement. The returned value can then be used in other parts of your program.

```python
def add(x, y):
    return x + y

result = add(5, 3)
print(result)  # Output: 8
```

**Recursion**

A recursive function is a function that calls itself. Recursion is useful for solving problems that can be broken down into smaller, self-similar subproblems.

```python
def factorial_recursive(n):
    if n == 0:
        return 1
    else:
        return n * factorial_recursive(n - 1)
```

**Practice Exercises**

1.  Given a list of numbers, create a function to find the sum of all positive numbers. [cite: 48]
   
2.  Write a Python function to check if a given string is a palindrome. [cite: 49]
   
3.  Implement a function that returns the factorial of a given number using recursion. [cite: 50]
   
4.  Create a function to find the square of each element in a given list. [cite: 51]
   
5.  Write a function to check if a number is even or odd and return "Even" or "Odd" accordingly. [cite: 52]
   
6.  Calculate the area of a triangle given its base and height using a function. [cite: 53]
   
7.  Create a function that takes a list of strings and returns the list sorted alphabetically. [cite: 54]
   
8.  Write a function that takes two lists and returns their intersection (common elements). [cite: 55]
   
9.  Implement a function to check if a given year is a leap year or not. [cite: 56]
   
10. Create a function that takes a number as input and prints its multiplication table. [cite: 57]

**Additional Resources**

* W3Schools Python Functions: [https://www.w3schools.com/python/python\_functions.asp](https://www.w3schools.com/python/python_functions.asp) [cite: 44]
   
* Real Python Defining Functions: [https://realpython.com/defining-your-own-python-function/](https://realpython.com/defining-your-own-python-function/) [cite: 44]

**Conclusion**

This chapter introduced the concept of functions and how to define and use them in Python. Functions are essential for writing organized, reusable, and maintainable code.