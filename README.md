[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15321318&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
  
   - Python is a high-level, general-purpose programming language created by Guido van Rossum in 1991. Pyrhon is  dynamically typed language.
   - Its ability to interpret code line by line, extensive library of open-source packages, platform independence, expressiveness, extensibility, and embeddable capabilities make it an ideal choice for many development projects.
   - Examples of use cases are Yotube, Insagram and Dropbox.
   - 

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   - First, you visit the python official website (python.org), then you go to download to download a version that suites your preferered operationg system - in my case windows operating system. then you follow the prompt.
   - To check if your have a version you will will type "py --version or python --version or python -v".

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   - print("Hello World")
   - In Python, we use the built-in print() function to display the string "Hello, World!"

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
     Numeric: These can be either integers or floats. ...
     Boolean: These are True/False values.
     String: These are text values composed of a sequence of characters.
     Sequence: These are collections of data types that can be the same or different.


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - Loops and conditional statements are powerful constructs that allow programmers to automate repetitive tasks and control the flow of their programs based on certain conditions.
    number = 10
    if number > 0:
    print('Positive number')
    else:
    print('Negative number')
    print('This statement always executes')

    iterate from i = 0 to i = 3
    for i in range(4):
    print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   -  These functions are built into the Python language and can be used without the need for additional code.
   -  def add_two_num(a,b):
    sum=a+b;
    return sum; 


7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - Lists are ordered collections of items, whereas the dictionary is an unordered collection of data in a key: value pair form.
   - numbers = [1,2,3,4,5,6,7]
   - thisdict = {
     "brand": "Ford",
     "model": "Mustang",
     "year": 1964
    }

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exceptions are errors that occur at runtime when the program is being executed. They are usually caused by invalid user input or code that is invalid in Python
   - try:
       # Some Code.... 
     except:
       # optional block
       # Handling of exception (if required)
     else:
       # execute if no exception
     finally:
      # Some code .....(always executed)

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
 A module in Python is a single file that contains Python code while a package is a collection of modules organized in a directory structure.
import math

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
   
    - with open("myfile.txt", "r") as file:
     content = file.read()
      print(content)

      def read_file_and_print(filename):
    try:
        with open(filename, 'r') as infile:
            content = infile.read()
            print(content)
    except FileNotFoundError:
        print(f"File '{filename}' not found.")

# Example usage:
read_file_and_print('example.txt')

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


