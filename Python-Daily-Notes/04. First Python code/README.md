# first python code and execution process
## 1. First Python code
#### The traditional first Python program is:
     print("Hello, World!")
#### Output:
     Hello, World!
### Explanation:
       print() is a built-in Python function.
       "Hello, World!" is a string.
       print() displays the string on the screen.
### how to run it in vs code
       Open VS Code.
       Create a file named first.py.
       Write:
       print("Hello, World!")
       Save the file.
       Click Run Python File ▶️.
## 2. Python Execution Process
### i. What is Python Execution?
Python execution is the process of taking Python source code, processing it, and producing the output.
### ii. Execution Flow
##### In Python, the standard Python implementation:
       Python Source Code (.py)
                 ↓
              Compiler
                 ↓
              Bytecode
                 ↓
        Python Virtual Machine (PVM)
                 ↓
              Execution
                 ↓
               Output
### iii. Step-by-step
#### write source code:
Source code is the original, human-readable instructions that a programmer writes to create a software program. It is written in programming languages such as Python, Java, C++, JavaScript, or C#.
##### Example:
       a = 10
       b = 20
       print(a + b)
#### compilation:
Python compiles the source code into bytecode.
##### Example:
       .py file
          ↓
       Bytecode
Bytecode may be stored in the __pycache__ directory as a .pyc file.
#### PVM Executes Bytecode:
The Python Virtual Machine (PVM) executes the bytecode.
#### Output:
The program produces:
30
### iv. Example Flow
       hello.py
          ↓
       Python Interpreter
          ↓
       Bytecode
          ↓
       PVM
          ↓
       print()
          ↓
       Hello Python
