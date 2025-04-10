
**Chapter 3: Control Flow and Loops in Python**

**Introduction**

This chapter dives into the essential concepts of control flow and loops in Python. Control flow allows you to determine the order in which statements are executed, enabling decision-making in your programs. Loops enable you to repeat a block of code multiple times, automating repetitive tasks. [cite: 569]

**Chapter Objectives**

* Understand conditional statements (`if`, `elif`, `else`) and how to use them to control the flow of execution. [cite: 569, 570]
   
* Learn about different types of loops in Python, including `for` loops and `while` loops, and how to use them for iteration. [cite: 569, 570]
   
* Apply control flow and loops to solve common programming problems.

**Conditional Statements**

Conditional statements allow your program to make decisions based on whether certain conditions are true or false.

* **`if` statement:** Executes a block of code if a condition is true.
   
* **`elif` statement:** (Else If) Checks an additional condition if the preceding `if` condition is false.
   
* **`else` statement:** Executes a block of code if all preceding conditions are false.

```python
number = int(input("Enter a number: "))

if number > 0:
    print("The number is positive.")
elif number < 0:
    print("The number is negative.")
else:
    print("The number is zero.")
```

**Loops**

Loops provide a way to execute a block of code repeatedly.

* **`for` loop:** Iterates over a sequence (e.g., list, string, range) and executes the code block for each item in the sequence.
   
    ```python
    fruits = ["apple", "banana", "cherry"]
    for fruit in fruits:
        print(fruit)
    ```
    
* **`while` loop:** Executes a block of code as long as a condition is true.
   
    ```python
    count = 0
    while count < 5:
        print(count)
        count += 1
    ```

**Practice Exercises**

1.  Create a program that takes a year as input and checks if it is a leap year or not. [cite: 573]
   
2.  Given a list of integers, find all the even numbers and store them in a new list. [cite: 574]
   
3.  Write a Python program to check if a given number is a prime number. [cite: 575]
   
4.  Create a program that generates the Fibonacci sequence up to a given number of terms. [cite: 576]
   
5.  Given a list of names, print all names starting with the letter 'A'. [cite: 577]
   
6.  Implement a program that prints the multiplication table of a given number. [cite: 578]
   
7.  Write a program that calculates the factorial of a given number. [cite: 579]
   
8.  Create a loop that prints all prime numbers between 1 and 50. [cite: 580]
   
9.  Given a list of words, count the number of words with more than five characters. [cite: 580]
   
10. Calculate the sum of digits of a given number. [cite: 581]

**Additional Resources**

* W3Schools Python Conditions: [https://www.w3schools.com/python/python\_conditions.asp](https://www.w3schools.com/python/python_conditions.asp) [cite: 570]
   
* Real Python Python Loops: [https://realpython.com/python-for-loop/](https://realpython.com/python-for-loop/) [cite: 570]

**Conclusion**

This chapter equipped you with the knowledge of control flow and loops, which are fundamental to creating programs that can make decisions and automate repetitive tasks. Mastering these concepts is essential for building more complex and efficient Python applications.