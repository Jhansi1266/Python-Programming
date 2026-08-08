# Modules and Pip
## 1. Modules
A module is a Python file containing reusable code that we can import and use in another Python program.
### Types of Modules:
There are 3 types
#### i. Built-in modules
These modules are ready to import and use with the python interpreter. there is no need to install such modules explicitly.
##### Examples:
      import math
      import os
      import random
#### ii. External modules
Created by other developers/organizations.Usually installed using pip.
##### Examples:
      pip install requests
      pip install pandas
#### iii. User-defined modules
Modules that you create yourself.
##### 
    #calculator.py
    def add(a, b):
        return a + b
##### Then:
      import calculator
## 2. pip(Pip Installs Packages)
### i. What is pip in Python?
PIP stands for Pip Installs Packages. It is Python's package manager used to install, upgrade, and uninstall external/third-party packages.
### ii. Simple understanding
#### You said:
Modules allow us to use someone else's code.

Exactly. pip helps you download and install many of those third-party packages so that you can use them in your Python programs.
### iii. Example
#### Suppose you want to use pandas:
      pip install pandas
#### After installation:
      import pandas
#### So the process is:
      Python Program
            ↓
      Need external package
            ↓
      pip install pandas
            ↓
      Package gets installed
            ↓
      import pandas
            ↓
      Use pandas in your program
### iv. Common pip commands
    Command	                      Purpose
    pip install pandas	          Install package
    pip uninstall pandas	        Remove package
    pip list         	            Show installed packages
    pip show pandas	              Show package information
    pip install --upgrade         pandas	Upgrade package
## 3. Relationship
      Module → reusable Python code
      Package → collection of modules
      pip → installs/manages packages
      import → brings the module/package into your program
## 4. pip vs import
pip is used to install and manage Python packages, whereas import is used to make a module or package available in a Python program.
## 5. modules vs packages
A module is a single Python file containing reusable code, whereas a package is a directory that organizes multiple related modules and subpackages.
