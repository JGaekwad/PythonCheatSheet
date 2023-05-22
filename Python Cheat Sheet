# Python and Pandas Command Reference

This document can easily be read by an online Markdown reader such as https://dillinger.io/

## Python Basics

### Print Statement

- `print()`: Prints a specified message or value.
    Example: `print("Hello, World!")`
    Documentation: [Python Print Function](https://docs.python.org/3/library/functions.html#print)

- `sys.stdout`: Standard output stream that can be used with `print()` to redirect the output to a file or another stream.
    Example:
    ```python
    import sys
    with open('output.txt', 'w') as f:
        print("Hello, World!", file=f)
    ```
    Documentation: [sys.stdout](https://docs.python.org/3/library/sys.html#sys.stdout)

### Mathematical Expressions

- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`
- Exponentiation: `**`
- Modulo: `%`
- Floor Division: `//`

## Boolean Expressions

- Equal to: `==`
- Not equal to: `!=`
- Less than: `<`
- Greater than: `>`
- Less than or equal to: `<=`
- Greater than or equal to: `>=`
- AND: `and` or `&`
- OR: `or`
- NOT: `not`

## Conditional Statements

- `if`, `elif`, `else`: Executes different blocks of code based on different conditions.
    Example:
    ```python
    if condition1:
        # Code block to execute if condition1 is True
    elif condition2:
        # Code block to execute if condition2 is True
    else:
        # Code block to execute if none of the conditions are True
    ```
    Documentation: [Python If...Else](https://docs.python.org/3/tutorial/controlflow.html#if-statements)

## Loops

- `for`: Iterates over a sequence (e.g., list, tuple, string) and executes a block of code for each element.
    Example:
    ```python
    for item in sequence:
        # Code block to execute
        print(item)
    ```
    Documentation: [Python For Loops](https://docs.python.org/3/tutorial/controlflow.html#for-statements)

- `range()`: Generates a sequence of numbers within a specified range.
    Example: `for i in range(1, 5):`
    Documentation: [Python Range](https://docs.python.org/3/library/stdtypes.html#range)

- `while`: Repeatedly executes a block of code as long as a condition is True.
    Example:
    ```python
    while condition:
        # Code block to execute
    ```
    Documentation: [Python While Loops](https://docs.python.org/3/tutorial/introduction.html#first-steps-towards-programming)

### Exception Handling

- `try`, `except`: Catches and handles exceptions (errors) in code.
    Example:
    ```python
    try:
        # Code that might raise an exception
        # ...
    except ExceptionType:
        # Code to handle the exception
        # ...
    ```
    Documentation: [Python Exceptions](https://docs.python.org/3/tutorial/errors.html)

- `IOError`: An exception that is raised when an I/O (input/output) operation fails.
    Example: `except IOError as e:`
    Documentation: [Python IOError](https://docs.python.org/3/library/exceptions.html#OSError)

## Functions

- Defining a function:
    - `def function_name(parameters):`: Defines a function with specified parameters.
        Example:
        ```python
        def add_numbers(a, b):
            return a + b
        ```
        Documentation: [Defining Functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)

- Calling a function:
    - `function_name(arguments)`: Calls a function with specified arguments.
        Example:
        ```python
        result = add_numbers(3, 5)
        print(result)
        ```

## Date and Time

- `datetime`: Module for working with dates, times, and timestamps.
    Example:
    ```python
    from datetime import datetime
    now = datetime.now()
    print(now)
    ```
    Documentation: [datetime - Basic date and time types](https://docs.python.org/3/library/datetime.html)

## Regular Expressions

- Common regex characters:
    - `.`: Matches any character except a newline.
    - `*`: Matches zero or more occurrences of the preceding element.
    - `+`: Matches one or more occurrences of the preceding element.
    - `?`: Matches zero or one occurrence of the preceding element.
    - `[]`: Matches any character inside the brackets.
    - `|`: Matches either the expression before or after the pipe symbol.
    - `^`: Matches the start of a string.
    - `$`: Matches the end of a string.
    - `\d`: Matches any digit character (0-9).
    - `\w`: Matches any alphanumeric character or underscore.
    - `\s`: Matches any whitespace character.
    - `\b`: Matches a word boundary.
    Documentation: [Python Regular Expression HOWTO](https://docs.python.org/3/howto/regex.html)

## Other Functions

- `abs()`: Returns the absolute value of a number.
    [Documentation](https://docs.python.org/3/library/functions.html#abs)

## Pandas

### Importing Pandas

- `import pandas as pd`: Imports the Pandas library for data manipulation and analysis.
    Example: `import pandas as pd`
    Documentation: [Pandas Documentation](https://pandas.pydata.org/docs/)

### Creating a DataFrame

- `pd.DataFrame()`: Creates a DataFrame from data.
    Example: `df = pd.DataFrame(data)`
    Documentation: [Pandas DataFrame](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)

- `pd.DataFrame(columns)`: Creates an empty DataFrame with specified columns.
    Example: `df = pd.DataFrame(columns=['column1', 'column2'])`
    Documentation: [Pandas DataFrame](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.html)

### Reading and Writing Data

- Reading CSV:
    - `pd.read_csv()`: Reads a CSV file and creates a DataFrame.
        Example: `df = pd.read_csv('data.csv')`
        Documentation: [Pandas CSV File Reading](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html)

- Writing to CSV:
    - `df.to_csv()`: Writes the DataFrame to a CSV file.
        Example: `df.to_csv('output.csv', index=False)`
        Documentation: [Pandas DataFrame to CSV](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html)

- Reading Excel:
- `pd.read_excel()`: Reads an Excel file into a DataFrame.
    Example: `df = pd.read_excel('data.xlsx')`
    Documentation: [Pandas read_excel](https://pandas.pydata.org/docs/reference/api/pandas.read_excel.html)

- Writing to Excel:
    - `df.to_excel()`: Writes the DataFrame to an Excel file.
        Example: `df.to_excel('output.xlsx', index=False)`
        Documentation: [Pandas DataFrame to Excel](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_excel.html)

### Exploring Data

- Displaying the first few rows:
    - `df.head()`: Displays the first few rows of the DataFrame.
        Example: `df.head()`
        Documentation: [Pandas DataFrame.head](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.head.html)

- Checking data types of columns:
    - `df.dtypes`: Returns the data types of each column in the DataFrame.
        Example: `df.dtypes`
        Documentation: [Pandas DataFrame.dtypes](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.dtypes.html)

- Getting the index of a column:
    - `df.columns.get_loc('column_name')`: Returns the index position of a column in the DataFrame.
        Example: `df.columns.get_loc('column_name')`
        Documentation: [Pandas DataFrame.columns.get_loc](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.columns.html#pandas.DataFrame.columns.get_loc)

### Dataframe Operations

- Creating a Series:
    - `pd.Series()`: Creates a Series from data.
        Example: `s = pd.Series(data)`
        Documentation: [Pandas Series](https://pandas.pydata.org/docs/reference/api/pandas.Series.html)

- Appending rows to a DataFrame:
    - `df.append()`: Appends rows to an existing DataFrame.
        Example: `new_df = df.append(row_data, ignore_index=True)`
        Documentation: [Pandas DataFrame.append](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.append.html)

- Appending DataFrames:
    - `pd.concat()`: Concatenates multiple DataFrames vertically or horizontally.
        Example: `new_df = pd.concat([df1, df2], axis=0)`
        Documentation: [Pandas Concatenation](https://pandas.pydata.org/docs/user_guide/merging.html#concatenating-objects)

- Converting DataFrame columns to a list:
    - `df.columns.tolist()`: Converts DataFrame columns to a Python list.
        Example: `df.columns.tolist()`
        Documentation: [Pandas DataFrame.columns.tolist](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.columns.html#pandas.DataFrame.columns.tolist)

### Data Manipulation

- Selecting columns:
    - `df['column_name']`: Selects a single column from the DataFrame.
        Example: `df['column_name']`
        Documentation: [Pandas Indexing and Selecting Data](https://pandas.pydata.org/docs/user_guide/indexing.html)

- Filtering rows based on a condition:
    - `df[df['column_name'] > 10]`: Filters rows based on a condition.
        Example: `df[df['column_name'] > 10]`
        Documentation: [Pandas Boolean Indexing](https://pandas.pydata.org/docs/user_guide/indexing.html#boolean-indexing)

- Selecting rows and columns using index-based location:
    - `df.iloc[row_index, column_index]`: Selects specific rows and columns using integer-based indexing.
        Example: `df.iloc[0:5, 1:3]`
        Documentation: [Pandas Indexing and Selecting Data](https://pandas.pydata.org/docs/user_guide/indexing.html#integer-location-based-indexing)

- Dropping duplicate rows:
    - `df.drop_duplicates()`: Removes duplicate rows from the DataFrame.
        Example: `df.drop_duplicates()`
        Documentation: [Pandas DataFrame.drop_duplicates](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html)

- Renaming columns:
    - `df.rename(columns={'old_name': 'new_name'})`: Renames columns in the DataFrame.
        Example: `df.rename(columns={'old_name': 'new_name'})`
        Documentation: [Pandas DataFrame.rename](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rename.html)

- Dropping columns or rows:
    - `df.drop()`: Drops columns or rows from the DataFrame.
        Example: `df.drop(columns=['column1', 'column2'])`
        Documentation: [Pandas DataFrame.drop](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop.html)

- Checking if a value is in a column:
    - `df['column_name'].isin([value1, value2])`: Checks if values exist in a column.
        Example: `df['column_name'].isin([value1, value2])`
        Documentation: [Pandas DataFrame.isin](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isin.html)

- Sorting DataFrame by column:
    - `df.sort_values(by='column_name', ascending=False)`: Sorts the DataFrame by a specified column.
        Example: `df.sort_values(by='column_name', ascending=False)`
        Documentation: [Pandas DataFrame.sort_values](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html)

- Resetting the index:
    - `df.reset_index()`: Resets the index of the DataFrame.
        Example: `df.reset_index()`
        Documentation: [Pandas DataFrame.reset_index](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.reset_index.html)

- Counting values in a column:
    - `df['column_name'].value_counts()`: Returns a count of unique values in a column.
        Example: `df['column_name'].value_counts()`
        Documentation: [Pandas Series.value_counts](https://pandas.pydata.org/docs/reference/api/pandas.Series.value_counts.html)

- Checking if a column contains null values:
    - `df['column_name'].isnull()`: Checks if values in a column are null.
        Example: `df['column_name'].isnull()`
        Documentation: [Pandas DataFrame.isnull](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isnull.html)

- Filling null values with a specified value:
    - `df['column_name'].fillna(value)`: Fills null values in a column with a specified value.
        Example: `df['column_name'].fillna(value)`
        Documentation: [Pandas DataFrame.fillna](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.fillna.html)

- Calculating the sum of a column:
    - `df['column_name'].sum()`: Calculates the sum of values in a column.
        Example: `df['column_name'].sum()`
        Documentation: [Pandas DataFrame.sum](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sum.html)

- Finding the largest values in a column:
    - `df['column_name'].nlargest(n)`: Returns the n largest values from a column.
        Example: `df['column_name'].nlargest(5)`
        Documentation: [Pandas Series.nlargest](https://pandas.pydata.org/docs/reference/api/pandas.Series.nlargest.html)

- Rounding values:
    - `round()`: Rounds the values in the DataFrame to a specified number of decimal places.
        Example: `df.round(2)`
        Documentation: [Pandas DataFrame.round](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.round.html)

### Data Type Conversion

- Converting a column to float:
    - `df['column_name'] = df['column_name'].astype(float)`: Converts a column to the float data type.
        Example: `df['column_name'] = df['column_name'].astype(float)`
        Documentation: [Pandas DataFrame.astype](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html)

- Converting a column to string:
    - `df['column_name'] = df['column_name'].astype(str)`: Converts a column to the string data type.
        Example: `df['column_name'] = df['column_name'].astype(str)`
        Documentation: [Pandas DataFrame.astype](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.astype.html)

### Aggregation

- Calculating mean:
    - `df['column_name'].mean()`: Calculates the mean of a column.
        Example: `df['column_name'].mean()`
        Documentation: [Pandas DataFrame.mean](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.mean.html)

- Grouping and aggregating:
    - `df.groupby('column_name')['other_column'].sum()`: Groups the DataFrame by a column and calculates the sum of another column.
        Example: `df.groupby('column_name')['other_column'].sum()`
        Documentation: [Pandas GroupBy](https://pandas.pydata.org/docs/user_guide/groupby.html)

## Plotting

- `import matplotlib.pyplot as plt`: Imports the matplotlib library for plotting.
    [Documentation](https://matplotlib.org/stable/index.html)

- `plt.rcParams.update()`: Updates the global matplotlib configurations.
    [Documentation](https://matplotlib.org/stable/tutorials/introductory/customizing.html)

- Scatterplot:
    ```python
    plt.scatter(x, y)
    plt.show()
    ```
    Example: [Scatterplot Example](https://matplotlib.org/stable/gallery/shapes_and_collections/scatter.html)

- Line plot:
    ```python
    plt.plot(x, y)
    plt.show()
    ```
    Example: [Line Plot Example](https://matplotlib.org/stable/gallery/lines_bars_and_markers/simple_plot.html)

## SciPy

### Normal Distribution

- `from scipy.stats import norm`: Imports the norm module for normal distribution operations.
    [Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html)

- `norm.ppf()`: Percent point function (inverse of cumulative distribution function).
    [Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html#scipy.stats.norm.ppf)

- `norm.pdf()`: Probability density function.
    [Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html#scipy.stats.norm.pdf)

- `norm.cdf()`: Cumulative distribution function.
    [Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html#scipy.stats.norm.cdf)

## NumPy

- `np.array()`: Converts a list or tuple to a NumPy array.
    [Documentation](https://numpy.org/doc/stable/reference/generated/numpy.array.html)

### Miscellaneous

- Commenting code:
    - `#`: Single-line comment
    - `'''...'''` or `"""..."""`: Multi-line comment
    Example:
    ```python
    # This is a single-line comment

    '''
    This is a
    multi-line comment
    '''

    """
    This is another
    multi-line comment
    """
    ```

- Backslash (`\`): Used for line continuation to break long lines of code into multiple lines.
    Example:
    ```python
    long_line = "This is a very long line of code that \
    I want to break into multiple lines for readability."
    ```

- Printing output:
    - `print()`: Prints a specified message or value.
    Example: `print("Hello, World!")`
    Documentation: [Python Print Function](https://docs.python.org/3/library/functions.html#print)


## Conclusion

This is a basic reference guide for commonly used Python and Pandas commands. Feel free to refer back to this document when you need a quick reminder or clarification on syntax and usage.
