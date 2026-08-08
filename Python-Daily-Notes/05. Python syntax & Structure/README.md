# Comments, Indentation, Keywords & Identifiers
## 1. Comments:
A comment is a note in the code that is ignored by the Python interpreter and is used to explain the code.
### Uses
    Explains code
    Improves readability
### Types of Comments in Python
There are 2 commonly used types:
#### i. Single line comment
To write a comment just add a '#' at the start of the line.
#### Example:
     #This is a single line comment
     print("Hello")
#### Output:
     Hello
#### ii. Multi line Comment
To write multi-line comments yo can use '#' at each line or you can use the multiline string.
##### Example 1: The use of '#'
     #It will be execute a block of code if a specified condition is true.
     #if the condition is false then it will execute another block of code.
     p=7
     if(p>5):
        print(" p is greater than 5.")
     else:
        print("p is not greater than 5.")
##### output:
     p is greater than 5.
##### Example 2: The use of multiline string.
      """ This is an if-else statement.
      It will be execute a block of code if a specified condition is true.
      if the condition is false then it will execute another block of code."""
##### output:
p is greater than 5.
## 2. Python Indentation:
Indentation means the spaces at the beginning of a line of code. Python uses indentation to define a block of code.
### Example
    if age >= 18:
        print("Eligible")
        print("You can vote")
Here, the spaces before print() are indentation.
### Important Points
    Python uses indentation instead of { } to define code blocks.
    Usually, 4 spaces are recommended.
    Incorrect indentation causes an IndentationError.
## 3. Python Keywords
Keywords are reserved words in Python that have a predefined meaning and cannot be used as names for variables, functions, or classes.
### Example:
    if
    else
    for
    while
### python has 35 keywords given below
| Column 1  | Column 2 | Column 3   |
| --------- | -------- | ---------- |
| `and`     | `as`     | `assert`   |
| `async`   | `await`  | `break`    |
| `case`    | `class`  | `continue` |
| `def`     | `del`    | `elif`     |
| `else`    | `except` | `False`    |
| `finally` | `for`    | `from`     |
| `global`  | `if`     | `import`   |
| `in`      | `is`     | `lambda`   |
| `match`   | `None`   | `nonlocal` |
| `not`     | `or`     | `pass`     |
| `raise`   | `return` | `True`     |
| `try`     | `while`  | `with`     |
| `yield`   |          |            |
## 4. Python Identifiers:
An identifier is a name given to variables, functions, classes, modules, or other objects in Python.
### Example:
    name = "Jhansi"
    age = 22
    
    def calculate():
        pass
#### Here:
        name → identifier
        age → identifier
        calculate → identifier
### Rules for Identifiers
    Can contain letters, digits, and _
    Cannot start with a digit
    Cannot contain spaces or special characters
    Cannot be a Python keyword
    Python identifiers are case-sensitive
### valid identifiers
    name
    student_name
    age2
    _total
### invalid identifiers
    2name       # starts with digit
    student name # space
    student-name # hyphen
    class       # keyword




