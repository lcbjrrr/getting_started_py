 
**Chapter 12: Introduction to Pandas**

**Introduction**

This chapter introduces the Pandas library, a powerful and essential tool for data analysis in Python. Pandas provides data structures like DataFrames and Series, which are highly efficient for working with structured data.

**Chapter Objectives**

  * Understand the basics of Pandas DataFrames and Series.
  * Learn how to create DataFrames from various data sources (CSV files, dictionaries, etc.).
  * Learn how to access, manipulate, and analyze data within DataFrames.

**Pandas Data Structures**

  * **Series:** A one-dimensional labeled array capable of holding any data type (integers, strings, floats, Python objects, etc.). Think of it like a column in a spreadsheet.
  * **DataFrame:** A two-dimensional labeled data structure with columns of potentially different types. It's similar to a spreadsheet or a SQL table.

**Creating DataFrames**

  * From CSV files: `pd.read_csv()`
  * From dictionaries: `pd.DataFrame(dictionary)`
  * From lists: `pd.DataFrame(list_of_lists)`

**DataFrame Operations**

  * Selecting columns: `df['column_name']`
  * Selecting rows: `df.loc[label]` or `df.iloc[index]`
  * Filtering data: `df[df['column'] > value]`
  * Adding/removing columns: `df['new_column'] = ...`, `df.drop('column', axis=1)`
  * Grouping data: `df.groupby('column')`
  * Merging/joining DataFrames: `pd.merge()`, `df.join()`

**Practice Exercises**

1.  Given a CSV file, load it into a Pandas DataFrame and display the first 5 rows.
2.  Create a Pandas DataFrame from a dictionary containing student names and their scores.
3.  Write a program to select specific columns ('Name' and 'Age') from a DataFrame.
4.  Implement a function that filters a DataFrame to show only rows where 'Age' is greater than a given value.
5.  Given a DataFrame with sales data, calculate the total sales for each product.
6.  Create a new column 'Total' (Price \* Quantity) in a DataFrame.
7.  Write a program to sort a DataFrame by a specific column (e.g., 'Salary').
8.  Implement a function that groups a DataFrame by a categorical column and calculates the average value of a numerical column.
9.  Given two DataFrames, merge them based on a common column ('ID').
10. Write a program to handle missing values (fill with 0 or drop rows) in a DataFrame.
11. Create a function to read data from a CSV file, clean it (handle missing values), and return the cleaned DataFrame.
12. Write a program to calculate descriptive statistics (mean, median, std) for numerical columns in a DataFrame.
13. Implement a function to add a new row to a DataFrame.

**Additional Resources**

  * Pandas Official Documentation: [https://pandas.pydata.org/pandas-docs/stable/](https://pandas.pydata.org/pandas-docs/stable/)
  * Pandas Getting Started: [https://pandas.pydata.org/pandas-docs/stable/getting\_started/index.html](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)
  * Real Python Pandas Tutorials: [https://realpython.com/pandas-tutorials/](https://www.google.com/search?q=https://realpython.com/pandas-tutorials/)

**Conclusion**

This chapter provided an introduction to the Pandas library and its core data structures, Series and DataFrames. You learned how to create, manipulate, and analyze data using Pandas, which is crucial for effective data science and analysis in Python.