



--------------------







1. What is Python?
Python is a high-level, general-purpose programming language.
It allows us to communicate instructions to a computer.
For example, imagine you want a computer to:
- Calculate mathematical equations.
- Analyze engineering data.
- Predict house prices using AI.
- Automate repetitive tasks.
- Scan networks for cybersecurity analysis.
- Build websites and applications.
Python can help you do all of these things.
Why is Python so popular?
Feature	Explanation
Easy syntax	Easy to read and write
Versatile	Used in many engineering fields
AI & ML	Excellent machine learning ecosystem
Automation	Automates repetitive tasks
Open source	Free to use
Libraries	Thousands of reusable tools

2. Install Python and prepare your environment
Python

Programming language interpreter
Download Python

Visual Studio Code

Code editor
Download VS Code

Since you're working with VS Code, we'll use it throughout this course.

After installation:
1. Open VS Code.
2. Install the Python extension from Microsoft.
3. Create a folder called Python_Course.
4. Create a file called lesson01.py.
5. Write your first Python program.
3. Your first Python program
Let's start with the most famous programming example.


print("Hello, World!")

Output:
Hello, World!


Congratulations! This is your first Python instruction.
Understanding the code
Let's break it down:
- print → A built-in Python function.
- () → Parentheses contain the information passed to the function.
- "Hello, World!" → A string (text).
- The computer displays the text in the terminal.
Another example:
print("My name is Ahmed")print("I am learning Python")print("My goal is to become a professional engineer")



Output:
My name is Ahmed
I am learning Python
My goal is to become a professional engineer


Important: Python executes instructions sequentially, meaning from top to bottom.
4. Comments in Python
Comments are notes written inside your code.

Python ignores comments when executing your program.

We use the # symbol.
# This is my first Python program

print("Hello!")

# This line calculates a mathematical operation
print(10 + 20)


Output:
Hello!
30

Comments are useful for explaining complicated code and documenting projects.
5. Python variables
Very important concept
A variable is a named reference to a value stored in memory.

Think of a variable as a label associated with information.

For example:

name = "Ahmed"
age = 23
country = "Algeria"
height = 1.78

Let's understand:
Variable	Value	Data
name	Ahmed	Text
age	23	Integer
country	Algeria	Text
height	1.78	Decimal

We can display variables using print():

name = "Ahmed"
age = 23

print(name)
print(age)

Output:
Ahmed
23


We can also combine variables:
name = "Ahmed"age = 23print("My name is", name)print("My age is", age)



Output:
My name is Ahmed
My age is 23


Important variable naming rules
Correct:
first_name = "Ahmed"age = 23student_grade = 15.5



Incorrect:

Python is case-sensitive:
name = "Ahmed"Name = "Mohamed"print(name)print(Name)



These are two different variables.
6. Basic data types
Python has several fundamental data types.
1. Integer (int)

Whole numbers without decimal points.
age = 23temperature = -5quantity = 100





2. Float (float)

Numbers with decimal points.
price = 19.99voltage = 220.5pi = 3.14159





3. String (str)

Text enclosed in quotation marks.
name = "Ahmed"university = "IGEE"language = "Python"





4. Boolean (bool)

Logical values: True or False.
is_student = Trueis_graduated = False





How can we identify a variable's data type?
We use the built-in type() function.

age = 23
height = 1.78
name = "Ahmed"
is_student = True

print(type(age))
print(type(height))
print(type(name))
print(type(is_student))
Output:
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>


Remember these four types. You'll use them constantly.
7. Basic mathematical operations
Python can work as a powerful calculator.

Operator	Meaning	Example	Result
+	Addition	10 + 5	15
-	Subtraction	10 - 5	5
*	Multiplication	10 * 5	50
/	Division	10 / 5	2.0
//	Floor division	11 // 2	5
%	Modulus (remainder)	11 % 2	1
**	Power	2 ** 3	8

Try this program:
a = 10b = 3print(a + b)print(a - b)print(a * b)print(a / b)print(a // b)print(a % b)print(a ** b)



Output:
13
7
30
3.3333333333333335
3
1
1000
