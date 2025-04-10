 
**Chapter 9: Object-Oriented Programming in Python**

**Introduction**

This chapter introduces the fundamental concepts of Object-Oriented Programming (OOP). OOP is a programming paradigm that revolves around objects, which are self-contained entities that encapsulate data and behavior.

**Chapter Objectives**

  * Understand the core principles of OOP: classes, objects, attributes, and methods.

  * Learn how to define classes and create objects in Python.

  * Learn how to define attributes and methods within a class.

  * Understand how to use `__init__` method for object initialization.

**Core Concepts of OOP**

  * **Class:** A blueprint or template for creating objects. It defines the attributes (data) and methods (behavior) that objects of that class will have. [cite: 86, 87, 88]

  * **Object:** An instance of a class. It is a concrete entity that has its own data and can perform actions defined by the class's methods. [cite: 86, 87, 88]

  * **Attribute:** A variable that stores data within an object. It represents a characteristic or property of the object. [cite: 89, 90, 91]

  * **Method:** A function that is defined within a class and can be called on objects of that class. It represents an action that the object can perform. [cite: 86, 87, 88]

**Defining Classes and Creating Objects**

  * **Class Definition:** Use the `class` keyword to define a class.

    ```python
    class MyClass:
        # Class attributes and methods
        pass
    ```

  * **Creating Objects:** Create objects (instances) of a class by calling the class as if it were a function.

    ```python
    my_object = MyClass()
    ```

**Attributes and Methods**

  * **Attributes:**
      * Attributes are defined inside the class.
      * They can be accessed using the dot notation (e.g., `object.attribute`).
  * **Methods:**
      * Methods are functions defined inside the class.
      * The first parameter of a method is always `self`, which refers to the object itself.
      * Methods are also accessed using dot notation (e.g., `object.method()`).
  * **`__init__` Method:**
      * The `__init__` method is a special method called a constructor.
      * It is automatically called when an object is created.
      * It is used to initialize the object's attributes.

**Practice Exercises**

1.  Create a class to represent a Student with attributes like name, age, and grades. [cite: 89]

2.  Given a CSV file with employee details (name, position, salary), create a class to represent an Employee. [cite: 89]

3.  Implement a program that simulates a basic bank account using a BankAccount class. [cite: 89]

4.  Write a Python program that uses a Rectangle class to calculate the area and perimeter of a rectangle. [cite: 89]

5.  Create a class to represent a Car with attributes like make, model, and year. [cite: 89]

6.  Given a JSON file with customer data, create a Customer class to store and manipulate the data. [cite: 89, 90, 91]

7.  Write a program that uses a Person class to keep track of a person's name, age, and address. [cite: 90]

8.  Implement a program that uses a Circle class to calculate the area and circumference of multiple circles. [cite: 88, 90]

9.  Given a CSV file with product details (name, price, quantity), create a Product class to manage the data. [cite: 90]

10. Create a class to represent a Movie with attributes like title, director, and rating. [cite: 90, 91]

**Additional Resources**

  * W3Schools Python Classes: [https://www.w3schools.com/python/python\_classes.as](https://www.google.com/search?q=https://www.w3schools.com/python/python_classes.as) [cite: 86]

  * Real Python Python OOP: [https://realpython.com/python3-object-oriented-programming/](https://realpython.com/python3-object-oriented-programming/) [cite: 86]

**Conclusion**

This chapter introduced the fundamental concepts of Object-Oriented Programming (OOP) in Python. You learned how to define classes, create objects, and work with attributes and methods. OOP is a powerful paradigm that promotes code organization, reusability, and maintainability.