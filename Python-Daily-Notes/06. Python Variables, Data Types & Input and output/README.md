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
