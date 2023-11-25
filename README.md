# Simple-Python-Calculator-
The Python Mini Calculator is a concise command-line application built for basic arithmetic operations. Perfect for beginners, this user-friendly project allows quick calculations with support for addition, subtraction, multiplication, and division.


first = input("enter first number : ")
operator = input("enter operator (+),(-),(/),(*),(%) : ")
second = input("enter second number : ")
 
 
first = int(first)
second = int(second)
if operator == "+":
    print(first + second)
elif operator == "-":
    print (first - second)
elif operator == "*":
    print (first * second)
elif operator == "/":
    print (first / second)
elif operator == "%":
    print (first % second)
 
else:
    print("Error")
