 
**Chapter 10: Inheritance and Encapsulation in Object-Oriented Programming**

**Introduction**

This chapter delves into two important concepts in Object-Oriented Programming (OOP): inheritance and encapsulation. Inheritance allows you to create new classes based on existing ones, promoting code reuse and a hierarchical structure. Encapsulation helps you protect the internal state of objects by controlling access to their attributes.

**Chapter Objectives**

  * Understand the concept of inheritance and its benefits.

  * Learn how to create derived classes from a base class.

  * Learn how to override methods in derived classes.

  * Understand the concept of encapsulation and its importance.

  * Learn how to implement encapsulation using private attributes in Python.

  * Define methods to get and set the values of private attributes.

**Inheritance**

  * **Base Class:** The original class that other classes inherit from. Also known as a superclass or parent class.

  * **Derived Class:** A new class created from a base class. It inherits the attributes and methods of the base class and can also have its own unique attributes and methods. Also known as a subclass or child class.

  * **Method Overriding:** The ability of a derived class to provide a different implementation for a method that is already defined in its base class.

**Encapsulation**

  * **Encapsulation:** The mechanism of hiding the internal state of an object and restricting access to it from outside the object. This is achieved by bundling the data (attributes) and methods that operate on that data within a class.

  * **Private Attributes:** Attributes that are intended to be accessed only from within the class. In Python, a common convention to indicate a private attribute is to prefix its name with a double underscore (e.g., `__my_attribute`).

  * **Getter and Setter Methods:** Methods that are used to access (get) and modify (set) the values of private attributes. They provide a controlled way to interact with the object's internal data.

**Practice Exercises**

1.  Create a base class `Animal` with a method `sound()` and create derived classes `Dog` and `Cat` with their own `sound()`. [cite: 93]

2.  Implement a class hierarchy to represent different types of vehicles (`Car`, `Bike`) with their own attributes and methods. [cite: 94]

3.  Create a class `Person` with private attributes and define methods to get and set the values of those attributes. [cite: 95]

4.  Create a base class `Shape` with methods to calculate area and perimeter, and derive classes `Circle` and `Square`. [cite: 97]

5.  Implement a class hierarchy to represent different types of employees (`Manager`, `Engineer`) with their attributes. [cite: 97]

6.  Write a Python program that uses inheritance to represent a hierarchy of shapes (`Triangle`, `Rectangle`, etc.). [cite: 97]

7.  Create a class hierarchy to represent different types of animals (`Bird`, `Fish`) with their own attributes and methods. [cite: 97]

8.  Given a JSON file with product details, create a `Product` class with encapsulated attributes. [cite: 97]

9.  Implement a program that uses inheritance to represent a hierarchy of vehicles (`Car`, `Bike`, `Truck`, etc.). [cite: 97, 98]

10. Write a Python program that uses encapsulation to protect sensitive information in a `User` class. [cite: 98]

11. Create a class hierarchy to represent different types of electronics (`Phone`, `Laptop`) with their attributes. [cite: 99]

12. Given a CSV file with employee details, create an `Employee` class with private attributes. [cite: 100]

13. Implement a program that uses inheritance to represent a hierarchy of shapes (`Circle`, `Triangle`, `Rectangle`, etc.). [cite: 101]

**Additional Resources**

  * W3Schools Python Inheritance: [https://www.w3schools.com/python/python\_inheritance.asp](https://www.google.com/search?q=https://www.w3schools.com/python/python_inheritance.as) [cite: 92]
  * Real Python Inheritance and Composition: [https://realpython.com/inheritance-composition-python/](https://realpython.com/inheritance-composition-python/) [cite: 93]

**Conclusion**

This chapter explained inheritance and encapsulation, two essential pillars of OOP. Inheritance enables code reuse and hierarchical organization, while encapsulation protects data integrity by controlling access. Understanding and applying these concepts leads to more robust, maintainable, and well-structured Python code.