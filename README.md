# PYTHON-JOURNEY-WITH-DANIEL-FROM-SCRATCH

# TABLE OF CONTENTS
- ## 📖 INTRODUCTION.
- [ABOUT THIS REPOSITORY.](#about-this-repository)
- [WHO THIS COURSE IS FOR:](#who-this-course-is-for)
- [HOW TO USE THIS REPOSITORY.](#how-to-use-this-repository)

- ## 🛠 SETUP & INSATLLATION
- [INSTALL VS CODE](#install-vs-code)
- [INSTALL PYCHARM](#install-pycharm)

- ## 🚀 PYTHON FUNDAMENTALS
- ### LESSON 1: Getting Started.
  - [WHAT IS PYTHON?](#what-is-python)
  - [WRITING YOUR FIRST PYTHON PROGRAM.](#writing-your-first-python-program)
  - [UNDERSTANDING print()](#understanding-print)
- ### LESSON 2: VARIABLES
  - [WHAT ARE VARIABLES?](#what-are-variables)
  - [VARIABLE NAMING RULES](#variable-naming-rules)
- ### LESSON 3: DATA TYPES
  - [BASIC DATA TYPES](#basic-data-types)
  - [TYPE CONVERSION](#type-conversion)
- ### LESSON 4: USER INPUT
  - [USING input()](#using-input)
  - [CONVERTING USER INPUT](#converting-user-input)

- ## 🔢 OPERATORS & EXPRESSIONS
- [ARITHMETIC OPERATORS](#arithmetic-operators)
- [COMPARISON OPERATORS](#comparison-operators)
- [LOGICAL OPERATORS](#logical-operators)

- ## 🔁 CONTROLFLOW
- ### CONDITIONALS
  - [IF, ELIF, ELSE](#if-elif-else)
- ### LOOPS
  - [FOR LOOPS](#for-loops)
  - [RANGE() FUNCTION](#range()-function)
  - [WHILE LOOPS](#while-loops)
  - [LOOP CONTROL (break & continue) ](#loop-control-(break-&-continue))
- ### 📦 DATA STRUCTURES
  - [LISTS](#lists)
  - [TUPLES](#tuples)
  - [DICTIONARIES](#dictionaries)
  - [SETS](#sets)
- ### 🧠 Functions
- [FUNCTIONS](#functions)
- [PARAMETERS & ARGUMENTS](#parameters--arguments)
- [RETRUN VALUES](#return-values)

## 📖 INTRODUCTION.
### ABOUT THIS REPOSITORY.
My Python learning journey from scratch — covering basics, practice problems, and projects which will be covered in the next 12 weeks of programming.
### WHO THIS COURSE IS FOR:
This course is for:
- Complete beginners with no programming experience
- Students who want to strengthen their Python basics
- Anyone preparing for coding courses or technical studies
- Self-learners who prefer structured, practical lessons\
If you are willing to practice and stay consistent, this course is for you.
### HOW TO USE THIS REPOSITORY.
To get the best results:
1. Follow the lessons in order.
2. Read each explanation carefully.
3. Type the code yourself (don’t just copy and paste).
4. Complete all exercises and assignments.
5. Try the mini projects to test your understanding.\
> [!TIP]
> Learning programming requires practice. Write code every day, even if it’s small.

## 🛠 SETUP & INSATLLATION
### INSTALL VS CODE.
* **WHAT IS VS CODE?**\
Visual Studio Code (VS Code) is a lightweight and beginner-friendly code editor used for writing and running Python programs.
* **DOWNLOAD VS CODE**\
Go to the official VS Code download page:
[https://visualstudio.microsoft.com/downloads/].\
Choose the version that matches your operating system: Windows, macOS, Linux.
- **INSATLLING VS CODE**\
Open the downloaded installer file.\
Follow the installation steps shown on your screen.\
For Windows users, it is recommended to:
  - Check “Add to PATH”
  - Check “Open with Code” (optional but helpful)
* **LAUNCH VS CODE**\
Open VS Code after installation.\
You should see a welcome screen. This means the installation was successful.
* **INSTALL PYTHON EXTENSION**\
Open VS Code.\
Go to the Extensions tab.\
Search for Python.\
Install the extension by Microsoft.
<img width="250" height="450" alt="image" src="https://github.com/user-attachments/assets/190cf7b8-4bd1-4b8c-b304-4c49b19ed5a2" />


## INSTALL PYCHARM
* WHAT IS PYCHARM?\
PyCharm is a powerful Python-focused Integrated Development Environment (IDE) that provides tools specifically designed for Python development.
* DOWNLOAD PYCHARM\
Go to the official PyCharm download page:
[https://www.jetbrains.com/pycharm/download/?section=windows]
* INSTALLING PYCHARM\
Open the downloaded installer file.\
Follow the installation instructions.\
Use the default settings if you are unsure — they work well for beginners.
* LAUNCH PYCHARM\
Open PyCharm after installation.\
Select New Project when prompted.\
Make sure Python is selected as the interpreter.


## 🚀 PYTHON FUNDAMENTALS
## LESSON 1 - GETTING STARTED.
### WHAT IS PYTHON?
Python is a high-level programming language known for its simple and easy-to-read syntax. It is designed to be beginner-friendly while still being powerful enough for professional software development.\
Python is widely used in areas such as web development, data analysis, artificial intelligence, automation, scientific computing, and game development. Because of its clear syntax and large community, Python is one of the best programming languages for beginners to learn.

### WRITING YOUR FIRST PYTHON PROGRAM.
**VS CODE:**\
Open a new folder.\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/a47167f5-296d-4c65-bebe-627b5fea6298" />\
Click on new folder and create a new one for your python files.\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/100a1e18-5d57-4cf4-a805-716e63a98de2" />\
Click on new file and name it. Make sure it ends with ".py" to show it is a python file.\
<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/4c44ea43-3c8e-4259-afc8-e4232488fa08" />\
<img width="400" height="600" alt="image" src="https://github.com/user-attachments/assets/1e8a4cdf-0c9a-422b-a0ee-7ae5836db96f" />\
"print()" is a function that tells python to display whatever value kept in the bracket on the screen.\
"Hello World" is the text that is being displayed after being run.\
Once you're done, run the program and see what it displays.
> [!NOTE]
> ***In VS Code, right-click in your python coding space, select run python file and run it in terminal.***
> <img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/ec520940-3e39-4da8-bba6-93dd5e1450c2" />

**PYCHARM**:\
Go to main menu, files.\
<img width="400" height="200" alt="image" src="https://github.com/user-attachments/assets/c54d4c39-5a51-4044-bde0-034791563c02" />\
Click on create after naming the python project.\
<img width="600" height="500" alt="image" src="https://github.com/user-attachments/assets/0345ed40-b66a-4b84-ad4f-6f67edf2d149" />\
Create a new python file.\
<img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/775fb9ad-d8b7-42cb-802a-8e7b9ac4145c" />\
It should look like this.\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/0d359bc8-8a03-4c46-a4f6-6fa8fd24745e" />\
After that you can now start with typing you first python script.\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/87f76381-837c-4d4d-8de5-5c007022b9a6" />\
Once you're done, run the program and see what it displays.

### UNDERSTANDING print()
The print() function is used to display output in Python. It allows you to show messages, numbers, or results on the screen.\
This tells Python to display the text inside the quotation marks.\
You can also print:
- Numbers → print(10)
- Variables → print(name)
- Calculations → print(5 + 3)\
In simple terms, print() is how your program communicates with the user.

## LESSON 2: VARIABLES
### WHAT ARE VARIABLES?
- Descriptive
- Lowercase
- Use underscores(is_students)
age = 25 
name = "DANIEL"  
height = 5.6  
print(age, name, height)\
Variables store values.
### VARIABLE NAMING RULES
Variable names should be:
<img width="3070" height="392" alt="image" src="https://github.com/user-attachments/assets/bed0896d-54d3-4c71-a9d5-a2faa1282e08" />

## LESSON 3: DATA TYPES
### BASIC DATA TYPES
There are different datatypes in python:
* int → Whole numbers (e.g., 10)  
* float → Decimals (e.g., 3.14)  
* str → Text (e.g., "hello")  
* bool → True / False      
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/042b6816-f779-4933-b072-3b1a33ed7363" />\
The "type()" function shows the datatype of your variable.
### TYPE CONVERSION
Data type conversion (also called type casting) means changing a value from one data type to another.\
For example, input from the user is always stored as a string, even if they type a number.\
Common conversion functions:
- int() → Converts to integer
- float() → Converts to float
- str() → Converts to string
- bool() → Converts to boolean
Type conversion is important when working with user input, calculations, and data processing.
<img width="800" height="250" alt="image" src="https://github.com/user-attachments/assets/a310f78a-1b0a-4d79-b444-435e2e4bfe8a" />

## LESSON 4: USER INPUT
### USING input()
Python can also take input from user and give the result as output.
name = input("Enter your name: ")  
print("Hello", name) 
### CONVERTING USER INPUT
<img width="1000" height="200" alt="image" src="https://github.com/user-attachments/assets/70745c40-7d47-4977-8fd2-4e77a6406e48" />

## 🔢 OPERATORS & EXPRESSIONS
### ARITHMETIC OPERATORS
Arithmetic operators are used to perform mathematical calculations.\
Common arithmetic operators:
- ' + ' → Addition
- ' - ' → Subtraction
- ' * ' → Multiplication
- ' / ' → Division
- ' % ' → Modulus (remainder)
- ' ** ' → Exponent (power)
- ' // ' → Floor division\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/309da9ae-85f6-4227-8858-0d3603ffcac7" />\
These operators allow Python to perform calculations using numbers stored in variables.
### COMPARISON OPERATORS
Comparison operators are used to compare two values.\
They return either True or False.\
Common comparison operators:
- ' == ' → Equal to
- ' != ' → Not equal to
- ' > ' → Greater than
- ' < ' → Less than
- ' >= ' → Greater than or equal to
- ' <= ' → Less than or equal to\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/105ef23c-27e3-4677-95d6-0d53b6bfeb73" />\
They are commonly used in decision-making (like if statements).
### LOGICAL OPERATORS
Logical operators are used to combine multiple conditions.
Common logical operators:
- 'and' → Returns True if both conditions are True
- 'or' → Returns True if at least one condition is True
- 'not' → Reverses the result (True becomes False, and vice versa)\
<img width="600" height="800" alt="image" src="https://github.com/user-attachments/assets/224f6cb6-0f9d-4468-83bd-71a92624ac17" />\
Logical operators are mainly used in conditional statements.

## 🔁 CONTROLFLOW
### CONDITIONALS
#### IF, ELIF, ELSE
IF Statement.\
Checks a condition. If true, executes the indented code block. It's the starting point for conditional logic.\
ELIF Statement.\
Short for "else if". Checks another condition only if the previous if or elif was false. Allows multiple conditions.\
ELSE Statement.\
Runs its code block if all prior if and elif conditions are false. No condition needed; acts as the default case.\
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/b3fe783b-2451-48a7-a5ec-1f578a775276" />
### LOOPS
#### FOR LOOPS
Iterates over a sequence (like a list, range, or string). Executes the indented code block for each item.\
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/4ce3dafb-3863-43a6-8768-28cae526f127" />
#### RANGE() FUNCTION
Commonly paired with for to generate a sequence of numbers for looping (e.g., for i in range(5) loops 0 to 4).
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/3d977479-b50f-4f48-9a1d-df0a7c2ebc5d" />
#### WHILE LOOPS
Repeatedly executes the indented code block as long as its condition remains true. Tests the condition before each iteration.\
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/df31e348-966e-40e7-af35-5d81f15ca530" />
#### LOOP CONTROL(break & continue)
break exits the loop early; continue skips the rest of the current iteration and checks the condition again.
<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/3acae66b-797a-45a4-bb43-b01b9c64ddf6" />

### 📦 DATA STRUCTURES
#### LISTS
Lists are used to store multiple items in a single variable. They are ordered, changeable (mutable), and allow duplicate values.\
List is an ordered collection of items and is enclosed in [].\
<img width="400" height="80" alt="image" src="https://github.com/user-attachments/assets/f1a72ef8-e254-48e4-9de5-bb206bfa9009" />\
**ACCESSING ELEMENTS IN LIST**\
To find out how many elements are in a list, use 'print(len())'.\
len() shows how much element is in a list\
To pick a specific element, you use 'print(lst(-a number within the range of the list-))'. Also, when finding a specific element, the counting starts from 0.\
<img width="600" height="250" alt="image" src="https://github.com/user-attachments/assets/ddde97be-a303-436d-ba22-0e372773b03f" />\
**ADDING AND REMOVING ELEMENTS**\
<img width="600" height="250" alt="image" src="https://github.com/user-attachments/assets/22ce47e9-c15b-49d4-8937-c129fac5afbc" />\
**OTHER SPECIAL FUNCTIONS**\
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b26c6d02-8210-4851-b4aa-2cb600e48aaa" />\
#### TUPLES
Tuples are similar to lists but are ordered and unchangeable (immutable). Once created, their values cannot be modified.\
Tuples are useful when you want to store data that should not change.\
<img width="300" height="80" alt="image" src="https://github.com/user-attachments/assets/148061a9-3176-4f72-8abd-b6f975ef247a" />\
**CONVERTING LIST TO TUPLES**\
<img width="200" height="400" alt="image" src="https://github.com/user-attachments/assets/3d54d190-2e3d-4875-a27b-78d7b0724e5f" />\
**OTHER SPECIAL FUNCTIONS**\
<img width="750" height="200" alt="image" src="https://github.com/user-attachments/assets/4fc41dfd-9f19-445e-8ce1-35a81bea55b6" />
#### DICTIONARIES
Dictionaries store data in key-value pairs. Each key is unique and is used to access its corresponding value.\
They are useful for storing structured data.\
<img width="500" height="100" alt="image" src="https://github.com/user-attachments/assets/da51c3d3-9b90-4f52-9725-e9b2f35be0fd" />\
In dictionaries, there are 3 features you should know: Items, Values and Keys.\
<img width="750" height="200" alt="image" src="https://github.com/user-attachments/assets/c078eb93-38f5-438b-9c66-1ed2db9ff9cf" />\
**KEYS**\
<img width="450" height="120" alt="image" src="https://github.com/user-attachments/assets/22f8a54b-adf9-4d51-b957-c29c92cf2243" />\
**VALUES**\
<img width="450" height="120" alt="image" src="https://github.com/user-attachments/assets/b29e5255-a486-491e-96fb-bcc404a568c5" />\
**LOCATION IN DICTIONARIES**\
<img width="450" height="180" alt="image" src="https://github.com/user-attachments/assets/5e049c75-fb18-4812-81c8-1ae80234849b" />\
**DELETION IN DICTIONARIES**\
<img width="450" height="180" alt="image" src="https://github.com/user-attachments/assets/854beca1-99ca-44e6-b0f4-d79c45d74b4e" />\
**SETS**\
Sets are used to store unique values. They are unordered and do not allow duplicates.\
The duplicate value will be removed automatically.\
<img width="450" height="100" alt="image" src="https://github.com/user-attachments/assets/a16d2083-0260-4a86-aecc-26eb579d6fd6" />\
**UPDATING AND REMOVING**\
<img width="500" height="200" alt="image" src="https://github.com/user-attachments/assets/57b9bf73-e3e3-4422-b05d-692595f2a75d" />

## 🧠 Functions
### FUNCTIONS
A function is a reusable block of code that performs a specific task. Functions help make programs more organized, easier to read, and easier to reuse.\
In Python, functions are defined using the def keyword.This function will print a message when it is called.\
<img width="250" height="250" alt="image" src="https://github.com/user-attachments/assets/d6c40ab7-0ba9-4c35-a75b-64a60f628923" />
### PARAMETERS & ARGUMENTS
Parameters are variables listed inside the parentheses when defining a function.\
Arguments are the actual values you pass into the function when calling it.\
Here, name is the parameter, and "Daniel" is the argument.\
<img width="270" height="150" alt="image" src="https://github.com/user-attachments/assets/29d63d9a-3744-4f6b-ad22-cce37ffa7576" />
### RETRUN VALUES
A return value is the value that a function sends back after it finishes running.\
In Python, we use the return keyword to send a value back.\
<img width="250" height="130" alt="image" src="https://github.com/user-attachments/assets/01c8d385-7b6c-420e-8fd1-2ec4c68f61c7" />



