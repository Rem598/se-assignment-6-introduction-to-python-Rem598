[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15375215&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Answer:
   Python is a high-level, interpreted programming language known for its simplicity and readability. Key features include simplicity, versatility, and support for multiple programming paradigms. Python is popular for web development and  data science.



2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Answer:
In windows operating system, visit the official Python website and download the latest version for Windows.
Run the installer  and follow the prompts.
Keep the default installation location.
To verify the installation, open a command prompt and type  python --version




3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Answer:
   print("Hello, World!")
That is the program that prints hello world.
print() is used to dispaly text or values in the console.
"" is used to enclose a string which is a sequence of characters.



4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Answer:
1.Integer(int) represents whole numbers examples 34,0
2.Float represents decimal numbers like 4.5
3.String(str) represents text or character sequences like "Jane"
4.Boolean(bool) represents either True or False. It is used for logical conditions.

# Variables and Data Types
x = 7  # integer
y = 5.3  # float
name = "Joan"  # string
is_present = True  # boolean




5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

Answer:
Conditional statements are used to execute different lines of code based on specific conditions.

# Example of if-else statement
x = 10
if x > 8:
    print("x is greater than 8")
else:
    print("x is less than or equal to 8")

# Example of for loop
for i in range(5):
    print(i)





6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

Answer:
Functions in Python allow us to organize and reuse code.
# Function to add two numbers
def add_numbers(a, b):
    return a + b

# Calling the function
result = add_numbers(6, 1)
print("Sum:", result)  # Output: Sum: 7





7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
Answer:
Lists are ordered  collections of items accessed by index.
Dictionaries are unordered collections of key-value pairs.

# List of numbers
numbers = [1, 2, 3]

# Dictionary example
person = {'name': 'Alice', 'age': 25}

# Accessing elements
print(numbers[0])  # Output: 1
print(person['name'])  # Output: Alice

# Adding new element
numbers.append(4)
person['city'] = 'New York'




8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

Answer:
Exception handling  is what allows ypu to handle errors gracefully.

# Example of exception handling
try:
    result = 10 / 0  # Division by zero
except ZeroDivisionError:
    print("Error: Division by zero")
finally:
    print("Execution completed")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Answer:
   Modules are Python files containing functions, classes, and variables.
   Packages are directories of modules.

# Example using math module
import math

# Calculate square root
num = 16
sqrt = math.sqrt(num)
print("Square root of", num, "is", sqrt)




10. File I/O:

How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    
  Answer:
 # Opening a file
with open('myfile.txt', 'r') as file:
    content = file.read()
    print(content)

# Reading a  file
with open('myfile.txt', 'r') as file:
    for line in file:
        print(line.strip())  

# Writing to a file
data = ['Apple', 'Banana', 'Cherry']
with open('fruits.txt', 'w') as file:
    for fruit in data:
        file.write(fruit + '\n')







# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


