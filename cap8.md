 
**Chapter 8: File Handling in Python**

**Introduction**

This chapter introduces file handling in Python, covering how to read from and write to files. File handling is essential for interacting with data stored in external files, such as configuration files, data logs, and more.

**Chapter Objectives**

  * Understand the different modes for opening files (read, write, append).
  * Learn how to read data from text files.
  * Learn how to write data to text files.
  * Learn how to work with CSV files.

**Opening Files**

Before you can read or write to a file, you need to open it using the `open()` function. The `open()` function takes two main arguments: the file path and the mode. [cite: 80]

  * **Read Mode (`'r'`):** Opens the file for reading. The file pointer is placed at the beginning of the file.
  * **Write Mode (`'w'`):** Opens the file for writing. If the file exists, it is overwritten. If the file does not exist, it creates a new file for writing.
  * **Append Mode (`'a'`):** Opens the file for appending. The file pointer is placed at the end of the file. If the file exists, new data is added to the end. If the file does not exist, it creates a new file for writing.

**Reading Files**

You can read data from a file using methods like `read()`, `readline()`, or `readlines()`. [cite: 80]

  * `read()`: Reads the entire file content as a string.
  * `readline()`: Reads a single line from the file.
  * `readlines()`: Reads all lines from the file and returns them as a list of strings.

**Writing Files**

You can write data to a file using the `write()` or `writelines()` methods. [cite: 81]

  * `write()`: Writes a string to the file.
  * `writelines()`: Writes a list of strings to the file.

**Working with CSV Files**

CSV (Comma Separated Values) files are a common format for storing tabular data. Python's `csv` module provides functionality to read and write CSV files. [cite: 82, 83, 84]

**Practice Exercises**

1.  Write a Python program to copy the contents of one text file into another. [cite: 83]
2.  Given a CSV file with student names and scores, find the student with the highest score. [cite: 83]
3.  Implement a program that reads a text file and counts the number of words and lines in it. [cite: 83]
4.  Create a function that takes a list of sentences and writes them to a new text file, each on a new line. [cite: 83]
5.  Given a CSV file with employee details (name, age, salary), calculate the average salary of all employees. [cite: 83]
6.  Write a program that reads a CSV file and finds the total sales revenue for a specific product. [cite: 83, 84]
7.  Given a text file with a list of numbers, write a function that finds the sum of all numbers in the file. [cite: 84]
8.  Implement a program that reads a CSV file and generates a bar chart to represent the data using Matplotlib. [cite: 84]
9.  Write a function that reads a JSON file and extracts specific information from it. [cite: 84]
10. Given a CSV file with temperature data for each day of the week, find the average temperature for each day. [cite: 84, 85]

**Additional Resources**

  * W3Schools Python File Handling: [https://www.w3schools.com/python/python\_file\_handling.asp](https://www.google.com/search?q=https://www.w3schools.com/python/python_file_handling.as) [cite: 80]
  * Real Python Read and Write Files: [https://realpython.com/read-write-files-python/](https://realpython.com/read-write-files-python/) [cite: 80]

**Conclusion**

This chapter covered the fundamentals of file handling in Python. You learned how to open, read, write, and manipulate files, including CSV files. These skills are essential for working with persistent data storage and exchange in Python.