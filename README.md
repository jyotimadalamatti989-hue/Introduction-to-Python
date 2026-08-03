# Introduction-to-Python
Python is one of the most popular, versatile, and beginner-friendly programming languages in the world today. Created by Guido van Rossum and released in 1991, it emphasizes code readability and simplicity, allowing programmers to express concepts in fewer lines of code than languages like C++ or Java.
#Python programming fundamentals:
# 1. Variables and Data Types
 # Variables:
 Think of a variable as a labeled storage box in the computer's memory. You can store data inside this box and change it later. The label is the variable's name.
 # Data Types:
  This specifies what kind of data is stored inside that box. Computers process different types of data differently.
 # (Integer): Whole numbers without decimals. (e.g., age = 25, temperature = -5)
 # float (Floating-point): Numbers containing decimal points. (e.g., price = 99.99, pi = 3.14159)
# (String): Textual data enclosed in single or double quotes. (e.g., name = "Alice", greeting = 'Hello')
# bool (Boolean): Represents logical states. It can only hold one of two values: True or False. (e.g., is_ logged_ in = True)

# 2. Input and Output Operations:
Programs need to interact with users. This is done by taking data in and sending data out.
# Input: 
Receiving information from the user (typically via the keyboard). In Python, the input() function prompts the user and always reads the input as a String.
# Output:
Displaying results or messages onto the screen. In Python, the print() function handles this.
# Example:
user_ name = input("Enter your name: ") # Takes Input
print("Welcome, " + user_ name)        # Displays Output

 # 3. Operators 
Operators are special symbols used to perform calculations, make comparisons, or combine conditions.

# Arithmetic Operators:
Used to perform mathematical operations.+ (Addition), - (Subtraction), * (Multiplication), / (Division), and % (Modulus - returns the remainder of a division, e.g., 10 % 3 is 1).

# Comparison Operators: 
Used to compare two values. The result is always a Boolean (True or False).== (Equal to), != (Not equal to), > (Greater than), < (Less than), >= (Greater than or equal to).

# Logical Operators: 
Used to combine multiple conditions together. and: Returns True only if both conditions are true. or: Returns True if at least one condition is true. not: Reverses the logical state (turns True into False and vice versa).

# 4. Conditional Statements :
Conditional statements control the flow of your program. They allow the code to make decisions and execute different blocks of code based on whether a condition is true or false (like a crossroads).
Keywords used: if, elif (short for else if), and else.

# Example
score = 85

if score >= 90:
    print("Grade: A")
elif score >= 75:
    print("Grade: B")  # This block will execute
else:
    print("Grade: C")

# 5. Loops
Loops: are used to run a block of code repeatedly as long as a certain condition is met. They prevent you from writing the same code over and over again. 
# For Loop: 
Best used when you know in advance how many times you want to run the loop (e.g., iterating through a list of 5 items or counting from 1 to 10).
# While Loop: 
Best used when you do not know the exact number of iterations beforehand, and the loop must run until a specific condition changes to false.


 


