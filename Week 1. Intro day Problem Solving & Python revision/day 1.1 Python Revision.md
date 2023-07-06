# Python Revision Class - 1 Hour

## Introduction to Python

Python is a high-level, interpreted programming language known for its simplicity and readability. It's widely used in various domains, such as web development, data analysis, artificial intelligence, and more. Let's start with some basics.

## Variables and Data Types

In Python, we use variables to store values. They don't require explicit declaration and their data type is dynamically inferred. Python supports various data types like integers, floats, strings, booleans, and more. Let's see some examples:

**Code Example 1**:
```python
age = 25
name = "John Doe"
is_new = True
```

## Control Flow Statements
Control flow statements allow us to control the flow of execution in our programs. We have conditional statements like if-else and loops like for and while. Let's look at an example:

**Code Example 2**:

```python
num = 10
if num > 0:
    print("Positive number")
elif num == 0:
    print("Zero")
else:
    print("Negative number")

```

## Functions
Functions in Python help us divide our code into reusable blocks. They improve code organization and reusability. Let's see how to define and call a function:

**Code Example 3**:

```python
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")
```

## Lists and Dictionaries
Lists and dictionaries are two fundamental data structures in Python. Lists are ordered collections of elements, while dictionaries are key-value pairs. Let's see some examples:

**Code Example 4**:

```python
fruits = ["apple", "banana", "orange"]
person = {"name": "John", "age": 30, "city": "New York"}
```

## File Handling
Python provides convenient ways to read from and write to files. Let's see an example of reading and writing data to a file:

**Code Example 5**:
```python
# Reading from a file
file = open("data.txt", "r")
content = file.read()
print(content)
file.close()

# Writing to a file
file = open("output.txt", "w")
file.write("Hello, World!")
file.close()

```

## Error Handling
Errors are common in programming, but Python provides robust error handling mechanisms using try-except blocks. Let's see an example:

**Code Example 6**:

```python
try:
    num = 10 / 0
except ZeroDivisionError:
    print("Error: Division by zero")
```

## Modules and Packages
Python offers a vast ecosystem of modules and packages that extend its capabilities. We can import and use them in our programs. Let's see an example of using the math module: