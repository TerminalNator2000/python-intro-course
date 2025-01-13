# python-intro-course
Introduction to Python series.

Hi everyone! My name is Mark 'Markus' Nations, and I’m excited to introduce you to the world of Python programming . 
A little about me—I’m a Marine Corps Veteran and a dedicated software developer with experience in Ai/Ml, Optimization development, cybersecurity, DevSecOps, and ethical hacking. I’ve worked on projects ranging from building web applications to optimizing tools for advanced security purposes to training machine learning models & Ai at enterprise scale. My passion lies in teaching others how to think like problem-solvers and empowering them to create something meaningful through technology.

Today, I’ll guide you through the basics of Python, a programming language known for being beginner-friendly, versatile, and powerful. Whether you want to build websites, automate repetitive tasks, or dive into data science, Python is the perfect starting point. So good?

Let's talk about the hottest topic in technology today... Anyone want to guess what that is?
Ai, right?
AI IS the hottest topic in technology today, and Python has cemented itself as the go-to programming language for artificial intelligence. It's vast libraries, ease of use, and active community make Python the go to for AI development, from data preprocessing and model building to deployment and beyond. Whether you're a seasoned developer or just starting, mastering Python is key in the AI space!

If you don't have any experience with programming languages need to worry! You don’t need to have any prior experience. Python has a very easy to learn syntax.
We’ll begin with the very basics and build step by step. By the end of this lesson, you’ll have written your very first Python program—and hopefully, you’ll feel inspired to explore more.

So, let’s get started going over our main course objectives:
1. Understand what Python is and why it’s popular.
2. Write and run your first Python program.
3. We're going to learn the basic syntax and structure of Python.

Question: What comes to your mind when you hear the word programming? 
Answers: websites, applications, video games, AI....
You're all correct! We also have IoT devices, which are devices out in the wild that connect to the internet, typically via a cloud solution. We'll get to cloud providers and solutions sometime in the near future.

Question: So why learn python? I'll give you my top 3 reasons:
1. Python is easy to learn and from beginner to expert, most IDE's or integrated development environments, have what's called a linter.
   A. Who know's what a linter is?
   A1. lenter is a tool built into most ide's, not all, that automatically analyzes source code and identifies or flags issues, faulty syntax, bugs, vulnerabilities, ect. I personally use VS Code and their linter has a predictive code feature that's fairly robust and accurate... most of the time. We'll come back to that when we set up our development environments.
2. Python is the language that brings us apps like Instagram, YouTube, and yes even NetFlix, just to name a few that we've all used or at least have heard of.
3. Python's syntax is simple, almost like writing in plain English.
Fun Fact: Python is named after 'Monty Python' as in 'Monty Python and the search for the Holy Grail, not the snake.
How are we doing so far?
Any questions before we move on?
Great!

Now it's time for us to discuss some basic Python Vocabulary, these are terms that you'll need to know as we begin to delve into writing python programs.
1.Basic Syntax and Concepts:
Variable: A name assigned to a value (e.g., x = 10).
Data Type: The kind of data a value represents (e.g., int, str, float, list).
Indentation: Python uses indentation (spaces or tabs) to define blocks of code.
Comment: Text in code meant for explanation, not execution. Single-line comments start with #.

2. Data Types
Integer (int): Whole numbers (e.g., 10, -3).
Float (float): Numbers with decimals (e.g., 3.14, -0.5).
String (str): Text enclosed in quotes (e.g., "hello", 'world').
Boolean (bool): Logical values (True or False).
List: Ordered, mutable collection of items (e.g., [1, 2, 3]).
Tuple: Ordered, immutable collection (e.g., (1, 2, 3)).
Dictionary (dict): Key-value pairs (e.g., {'key': 'value'}).
Set: Unordered collection of unique items (e.g., {1, 2, 3}).

3. Control Flow
If Statement: Executes a block of code if a condition is true.
```python

if x > 0:
    print("Positive")
```
For Loop: Iterates over a sequence (e.g., a list).
```python

for item in [1, 2, 3]:
    print(item)
```
While Loop: Repeats as long as a condition is true.
```python

while x < 5:
    x += 1
```
Break: Exits the loop immediately.
Continue: Skips the current iteration and continues with the next.

4. Functions
Function: A block of reusable code defined using def.
```python

def greet(name):
    return f"Hello, {name}!"
```
Parameter: Variable used in function definition.
Argument: Value passed to a function.

5. Common Operators
Arithmetic Operators: + (add), - (subtract), * (multiply), / (divide), % (modulus), ** (exponentiation).
Comparison Operators: == (equal), != (not equal), <, >, <=, >=.
Logical Operators: and, or, not.

6. Object-Oriented Programming (OOP)
Class: A blueprint for objects.
```python

class Person:
    def __init__(self, name):
        self.name = name
```
Object: An instance of a class.
Method: A function defined inside a class.
Attribute: Variables tied to an object.

7. Error Handling
Try/Except: Catches and handles exceptions.
```python

try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero.")
```
8. Input/Output
Print: Outputs data.
```python

print("Hello, World!")
```
Input: Receives user input as a string.
```python

name = input("Enter your name: ")
```
9. File Handling
Open: Opens a file for reading, writing, or appending.
```python

with open("file.txt", "r") as file:
    content = file.read()
```
Read: Reads file content.
Write: Writes data to a file.

10. Libraries and Modules
Import: Loads external Python code.
```python

import math
```
Module: A Python file with reusable code (e.g., math, os, random).
Library: A collection of modules (e.g., NumPy, Pandas).


