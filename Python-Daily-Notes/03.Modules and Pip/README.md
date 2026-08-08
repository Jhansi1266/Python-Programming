# Python Environment & Setup
## 1. Python versions
Python has gone through three major version generations:
### i. Python 1
       Python 1.0 was the first official major release of Python, released in January 1994.
       It was Developed by Guido van Rossum.
       It established basic Python programming language.
       The first version of python is python 1.0.
       The last version of Python 2 is Python 1.6.
       It is obsolete and no longer supported.
       It is important mainly for Python history, not for modern development.
### ii. Python 2
       Python 2.0 was the second major version of Python. It was released in October 2000.
       It was Developed by Guido van Rossum.
       The first version of python is python 2.0.
       The last version of Python 2 is Python 2.7.
       Python 2 was widely used for web development, automation, scripting, data processing, system 
       administration, and software development, but it is now obsolete because official support 
       ended in 2020.
       Python 2 is not used for new development because it reached End of Life in 2020 and is no 
       longer officially supported. Python 3 replaced Python 2 and is the standard for modern 
       Python development.
### iii. Python 3
       Python 3 is the modern major version of Python and the version used for current Python 
       development.
       It was developed by Python community under the leadership of Guido van Rossum
       The first version is 3.0.
       The python presents version of python3 is python 3.14.6.
       Python 3 is a general-purpose programming language used for web development, data analysis,  
       AI/ML, automation, scripting, API development, DevOps, scientific computing, and many other 
       software applications.
       Python 3 was created to improve Python's language design and fix limitations in Python 2. It 
       introduced changes that made it not fully backward-compatible with Python 2.
## 2. Python Versions — Interview Questions & Answers
### i. What is the latest major version of Python?
Python 3.14 is the latest major/feature release as of August 2026.
### ii. Who created Python?
Guido van Rossum created Python.
### iii. When was Python first released?
Python was first officially released in 1994.
### iv. What are the major versions of Python?
The major versions are:
Python 1
Python 2
Python 3
### v. What was the last version of Python 1?
Python 1.6.
### vi. When was Python 2 released?
Python 2.0 was released in 2000.
### Vii. What was the last version of Python 2?
Python 2.7.
### viii. Is Python 2 still supported?
No. Python 2 officially reached End of Life on January 1, 2020.
### ix. Why is Python 2 obsolete?
Because it is no longer officially maintained or receiving security updates, and Python 3 replaced it.
### x. When was Python 3 released?
Python 3.0 was released on December 3, 2008.
### xi. Why was Python 3 introduced?
Python 3 was introduced to improve the language, fix design limitations, and provide a cleaner foundation for future development.
### xii. Is Python 3 backward-compatible with Python 2?
No, not fully. Some Python 2 code requires changes to run correctly in Python 3.
### xiii. What is the difference between Python 2 and Python 3?
“Python 2 and Python 3 are major versions of Python. Python 2 was discontinued on January 1, 2020, while Python 3 is the modern version. Major differences include print syntax, division behavior, input handling, Unicode support, and range behavior. For new projects, we use Python 3.”
### xiv. Which Python version should you learn today?
Python 3, because Python 2 is obsolete and modern Python development uses Python 3.
### xv. What is the difference between Python 3.10, 3.11, 3.12, etc.?
They are minor/feature releases within the Python 3 series. Each generally introduces new features, improvements, performance enhancements, and bug/security fixes.
### xvi. What is Python 3.14?
Python 3.14 is a major feature release within the Python 3 series, released in 2025.
### xvii. How do you check your Python version?
python --version
or:
python -V
Example:
Python 3.14.6
### xviii. What does Python 3.14.6 mean?
       Python 3.14.6
              │ │  │
              │ │  └── Patch/Maintenance version
              │ └───── Minor/Feature version
              └─────── Major version
### xix. What does obsolete mean?
Obsolete means old technology that has been replaced by newer technology and is no longer supported or recommended.
### xx. What is the difference between Python 1, Python 2, and Python 3?
Python 1 was the first major version of Python, Python 2 introduced significant improvements and was widely used for many years, and Python 3 was introduced as a major redesign with improved syntax, Unicode support, and modern language features. Python 1 and Python 2 are obsolete, while Python 3 is the modern Python series.
## 3. Python Installation & Setup.
### i. What is Python Installation?
Python installation is the process of installing the Python interpreter and supporting tools required to develop and execute Python programs.
### ii. Download Python
Download Python 3.x from the official Python website.
Python 3.14.6 is the modern version used for development.
### iii. Install Python
#### On Windows:
       Run the Python installer.
       Check Add Python.exe to PATH 
       Click Install Now.
       Complete the installation.
### iv. Python Interpreter
The Python interpreter reads and executes Python source code.
### v. PATH
PATH is an environment variable that allows the operating system to locate the Python executable from the command line.
### vi. Verify python Installation
#### Open Command Prompt and run:
      python --version
      or 
      python -V
#### Example Output:
     python 3.x.x
### vii. Interactive mode
       Write Python directly and get immediate output
       open Command promt and type:
       print("Hello")
       You immediately get:
       Hello
When is it useful?
Mostly for quick testing and learning small pieces of code.
### viii. pip-Installing Packages
#### What is a package?
A package is reusable code written by other developers that you can add to your Python project.
For example, you might need a package called requests.
##### You install it using:
      pip install requests
##### Then you can use it:
      import requests
##### Think:
       pip
        ↓
       Downloads package
        ↓
       Installs package
        ↓
       You can use package in Python
### ix. Standard Library
       Useful modules already included with Python
       math is part of Python's Standard Library.
#### Example:
       import math
       print(math.sqrt(25))
#### output:
     5
### x. IDLE(Integrated Development and Learning Environment)
IDLE stands for Integrated Development and Learning Environment. It is a basic IDE included with Python that provides a code editor, interactive Python shell, and debugging features for developing Python programs.
#### What can you do with IDLE?
     Write Python code
     Run Python programs
     Debug programs
     Create and edit .py files
### xi. VS Code + Python Extension
VS Code is a code editor.
You can write your Python programs in it.
#### Example:
     hello.py
#### inside the file:
     print("Hello Python")
The Python extension adds Python-specific features such as running code, debugging, code completion, and interpreter selection.
### xii. What is .py?
.py is the file extension used for Python source-code files.
#### Example:
       hello.py
       calculator.py
       student.py
       app.py
### xiii. python filename.py
              Create hello.py
                     ↓
              Write Python code
                     ↓
              print("Hello World")
                     ↓
              Run:
              python hello.py
                     ↓
              Python Interpreter executes it
                     ↓
              Hello World
### xvi. complete flow
       1. Download Python 3.x
                 ↓
       2. Install Python
                 ↓
       3. Add Python to PATH
                 ↓
       4. Python Interpreter
                 ↓
       5. Verify Python
          python --version
                 ↓
       6. Interactive Mode
          python → >>>
                 ↓
       7. pip
          pip install package
                 ↓
       8. Standard Library
                 ↓
       9. IDLE
                 ↓
       10. VS Code + Python Extension
                 ↓
       11. Create .py file
                 ↓
       12. Run Python Program
          python filename.py
## 4. What is python interpreter?
A Python interpreter is a program that executes Python code. In CPython, the source code is compiled into bytecode, and the bytecode is executed by the Python Virtual Machine (PVM).
## 5. What is Python Syntax?
Python syntax refers to the rules and structure used to write valid Python programs. Important syntax features include indentation, case sensitivity, variables, keywords, comments, colons for code blocks, and proper use of operators and expressions.
## 6. First Python code
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
## 7. Python Execution Process
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

              
