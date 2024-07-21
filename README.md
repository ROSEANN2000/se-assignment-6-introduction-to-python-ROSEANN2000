[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15382078&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

Python is a programming language used to build websites and software, conduct data analysis and automat tasks.
   Easy to Learn therefore, it's a biginner friendly language which can be quickly learnt.
   Easy to Use hence one can write less code to accomplish tasks
   Easy to Read since it used english words making it easy to understand. 
   Easy to Code making  it easy to write and test code.






2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.


Windows:

Download the installer: Head to the official Python downloads page [download python ON Python.org] and choose the latest Python 3 version under "Windows x86-64 executable installer" (for 64-bit systems) or "Windows x86 executable installer" (for 32-bit systems).

Run the installer: Double-click the downloaded file and follow the on-screen instructions.  Crucially, check the option to "Add Python 3.x to PATH" during installation. This allows you to run Python commands from any directory in your command prompt.

Verify installation: Open a command prompt (search for "cmd" in the Start menu) and type python --version. If Python is installed correctly, you'll see the installed version number.








3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.


print ("Hello, world!")

Values - Use quotation marks (" or ') around a string
Use decimal points (.) to turn an int into a float
Booleans can only be True or False
Functions - Use parentheses ( () ) after the name to use a function. Add the parameter between the parentheses if needed (like in print)
Comments - Use an octothorpe ( # ) to start a single-line comment.




4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.


text type - str (represents textual data containing numbers, symbols and spaces)
x = "Hello World"

Numeric Types:	int (contains whole numbers)
x = 10

sequence Types:	list (an ordered collection of elements)
x = ["apple", "banana", "orange"]

Mapping Type:	dict (an unordered collection of key-value pairs)
x = {"name" : "Rose", "age" : 21}

Set Types:	set (an unoredered collection of unique elements)
x = {"apple", "banana", "oranges"}

Boolean Type:	bool ( represents logical values)
x = True





5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.


Conditional statements and loops are fundamental constructs used to control the flow of execution in a program. They enable developers to create flexible and dynamic algorithms that can make decisions and iterate over data efficiently.

a = 20
b = 20
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
   
   fruits = ["apple", "banana", "orange"]
for fruit in fruits:
  print(fruit)







6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

fuctions are blocks of code that run when called performing specific tasks and helping in readability and maintainance.


def add_numbers (x, y):
  sum = x + y
  return sum

result = add_numbers (5, 3)
print(result)  







7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

A list is a collection of items in order while a dctionmary is unordered collection of key-value pairs. Both can be changed in terms of values.
Additionally, one accesses lists by numerical index while in dctionaries it's by key.
lists examples

x = ["10", "33", "45"] #list of ages n a household
y = ["5" , "1" , "9"]  # list of numbers

dictionaries

person = { " name": "Rose"
"age" : "21"
"country": "Kenya"
}


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

exception handling is a method for managing errors during execution.

def divide(numerator, denominator):

numerator = 20
denominator = 0
 try: result = numerator / denominator
 print("The result is:", result")

except ZeroDivisionError: 

    print("Error: Cannot divide by zero!")


finally:
    
    print("Division operation completed.")







9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

A module is a python file containing variables, classes and functions. Packages are a collecton of related modules.
 One way of importing a module is by clicking on "import"

EXAMPLE

 import math 

 result = math.sqrt(25)
 print("The square root of 25:", result)







10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

One can open a python file by clicking on the open (filename) then read using read().

def read_file (rose.py)

try:
with open (rose.py, 'r') as file:
content = file.read()

print(content)

Part 2

lines = [

   "Assignment 6",
   "Answer all questions",
   "Submission Guidelines"

]

with open ('rose.txt', 'w') as file

for line in lines:
        file.write(line + '\n')



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


