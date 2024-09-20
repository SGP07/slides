---
theme: shibainu
---

# Python Basics

Welcome to the world of Python!

---

# What is Python?

Python is a high-level, interpreted programming language that is easy to learn and understand.

---

# Variables and Data Types

In Python, a variable is a name given to a value. You can think of it as a labeled box where you can store a value.

### Basic Data Types

#### 1. Integers (int)
Whole numbers, e.g., `1`, `2`, `3`, etc.

#### 2. Floats (float)
Decimal numbers, e.g., `3.14`, `-0.5`, etc.

#### 3. Strings (str)
Sequences of characters, e.g., `"hello"`, `'hello'`, etc. Strings can be enclosed in single quotes or double quotes.

#### 4. Boolean (bool)
True or false values, e.g., `True`, `False`

---

# Variables and Assignment

You can assign a value to a variable using the assignment operator (`=`).

### Example
```
x = 5  # assign 5 to x
y = "hello"  # assign "hello" to y
```

---

# Lists

A list is a collection of items that can be of any data type, including strings, integers, floats, and other lists.

### Creating a List
```
fruits = ["apple", "banana", "cherry"]
```

### Indexing and Slicing
```
print(fruits[0])  # output: "apple"
print(fruits[1:3])  # output: ["banana", "cherry"]
```

---

# Dictionaries

A dictionary is a collection of key-value pairs.

### Creating a Dictionary
```
person = {"name": "John", "age": 30, "city": "New York"}
```

### Accessing Dictionary Values
```
print(person["name"])  # output: "John"
```

---

# Loops

Loops allow you to execute a block of code repeatedly.

### For Loop
```
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
```

### While Loop
```
i = 0
while i < 5:
    print(i)
    i += 1
```

---

# Functions

Functions are blocks of code that can be executed multiple times from different parts of your program.

### Defining a Function
```
def greet(name):
    print("Hello, " + name + "!")
```

### Calling a Function
```
greet("John")  # output: "Hello, John!"
```

---

# Conclusion

That's a wrap! You've learned the basics of Python, including variables, data types, lists, dictionaries, loops, and functions. Practice makes perfect, so start coding!