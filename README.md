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
- [Logical Operators](#logical-operators)

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


