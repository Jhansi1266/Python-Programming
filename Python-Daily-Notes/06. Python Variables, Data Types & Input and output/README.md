# variables, Constants, Datatypes, Typecasting, Input & output and Escape Sequences
## 1. Variable
A variable is like a container that holds data. Similar to how containers in a kitchen hold sugar, salt, etc., a variable holds a value in a Python program.
Creating a variable means creating a name that refers to a value.
### Example of creating variable:
    name = "Jhansi"
    age = 22
### Here:
    name     → variable
    "Jhansi" → value
    age      → variable
    22       → value
    =        → assignment operator
## 2. Constants
A constant is a value that should not be changed during program execution.
In Python, constants are usually written in uppercase letters to indicate that their values should not be changed.
### Example:
    PI = 3.14
    MAX_SIZE = 100
## 3. Data Types:
A data type specifies the type of value a variable holds. It helps Python determine what operations can be performed on that value.
In Python, we can find the type of a value using the type() function.
### Example:
    a=1
    print(type(a))
    b="1"
    print(type(b))
### output:
    <class 'int'> 
    <class 'str'>
### Python provides several built-in data types:
### 1. Numeric Types:
int: 3,-8,0
float: 7.34, -7.0, 0.01
complex: 6+2i
### 2. Text data:
str:"Hello"
### 3.Boolean Type: 
bool: Boolean data contains True or False values.
### 4. Sequance data:list, tuple.
list: A list is an ordered collection of data with elements separated by a comma and enclosed within square brackets. Lists are mutable and can be modified after creation.
#### Example:
     list1=[8,2.3,[-4,5],["apple","banana"]]
     print(list1)
#### output:
     [8,2.3,[-4,5],["apple","banana"]]
Tuple: A tuple is an ordered collection of data with elements separated by a comma and enclosed within parentheses. Tuples are immutable and can not be modified after creation.
#### Example:
     tuple1=(("parrot","sparrow"),("Lion","Tiger"))
     print(tuple1)
#### output
     (("parrot","sparrow"),("Lion","Tiger"))
### 5.Mapping Type – dict

range
Set Types – set, frozenset
### 5.Mapping Type – dict
Binary Types – bytes, bytearray, memoryview
None Type – NoneType
















### Escape Sequences in Python

An escape sequence is a special character combination beginning with a backslash (\) used to represent special characters inside a string.

Common Escape Sequences
Escape Sequence	Meaning	Example
\n	New line	"Hello\nWorld"
\t	Tab	"Hello\tWorld"
\\	Backslash	"C:\\Python"
\'	Single quote	'It\'s Python'
\"	Double quote	"He said \"Hi\""
\b	Backspace	"Hello\b"
\r	Carriage return	"Hello\rWorld"
Example
print("Hello\nWorld")

Output:

Hello
World
Interview Answer ⭐

An escape sequence is a combination of characters starting with a backslash (\) that represents a special character in a string.

Most important to remember:
\n → new line
\t → tab
\\ → backslash
\' → single quote
\" → double quote

more on print statement
Python print() Statement

The print() function is used to display output on the screen.

1. Basic print()
print("Hello World")

Output:

Hello World
2. Print multiple values
name = "Jhansi"
age = 22

print(name, age)

Output:

Jhansi 22

By default, print() adds a space between multiple values.

3. sep — Separator

sep specifies what should be placed between multiple values.

print("Python", "Java", "SQL", sep=" | ")

Output:

Python | Java | SQL
4. end — Ending Character

By default, print() ends with a new line (\n).

print("Hello", end=" ")
print("World")

Output:

Hello World

Without end:

print("Hello")
print("World")

Output:

Hello
World
5. Printing Variables
name = "Jhansi"
age = 22

print(name)
print(age)
6. Printing Expressions
a = 10
b = 20

print(a + b)

Output:

30
7. Printing with f-strings

Useful for combining text and variables:

name = "Jhansi"
age = 22

print(f"My name is {name} and I am {age} years old.")
8. Escape Sequences with print()
print("Hello\nWorld")

Output:

Hello
World
print("Name:\tJhansi")

Output:

Name:   Jhansi
9. Empty print()
print()

It prints a blank line.

⭐ Interview Points

print() is a built-in Python function used to display output.

Important parameters:

print(value, sep=' ', end='\n')
value → What to print
sep → Separator between multiple values
end → What to print at the end
Default sep → space
Default end → newline \n
Most important for beginners

Learn these first:

print() → multiple values → sep → end → escape sequences → f-strings.
