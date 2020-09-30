# Hello-World-
This repository contains material related to Python language.
 ASSIGNMENT 1st-- 29/9/2020---- AssignmentPython1-Intro
# 1.Predict Output: 
s1="Gaurav"
s2="tuteur.py@gmail.com"
print(len(s1),len(s2))

# 2.WAP to input a string and print its length. 
str_length=input("enter a string: ")
print("length of string:" ,len(str_length))

# 3.WAP to input 2 numbers and print their sum and difference. 
a=int(input("enter a number: "))
b=int(input("enter another number:"))     # DOUBT ???--- Can we input 2 numbers together
sum=a+b
diff=a-b
print("sum: ",sum,  "diff: ", diff )

# 4.Predict output: 
s1="ab"
s2="de"
s3=s1+s2
print(s3)

# 5.Predict output: 
s1="ab"
s2="de"
s3=s1+s2
print(s3)

# 6.Predict output:
s1="ab"*4
print(s1)

# 7.Predict output: 
s1="ab\n"*4
print(s1)

# 8.WAP to input a string s and a number n. Print the string n times on the screen, each should appear in a separate line 
#(do not use any kind of loops, use the multiplication operator). 
s=input("enter a string:") + "\n"   #to print in a separate line
n=int(input("enter a number:"))
result=s*n
print("result: \n", result)    

# 9.Predict Output: 
res=print("Gaurav")
print(res)

# 10.Predict Output:
res=len("tuteur.py@gmail.com")
print(type(res))

# 11.Predict Output: 
s1="Gaurav"
s2="tuteur.py@gmail.com"
s3=s1 +"\n" + s2
print(type(s3))
print(len(s3))

# 12.Find the name of function to find the square root. (see all the options available in dir() of math) 
help("math")
help("math.sqrt")

# 13.WAP to input a number and print its square root (). 
import math
x=int(input("enter a number:"))
math.sqrt(x)
print("sqrt of x:", math.sqrt(x))   

# 14.WAP to input 4 numbers from user and print their average 
print("enter 4 numbers")
a=int(input("enter a number: "))
b=int(input("enter a number: "))
c=int(input("enter a number: "))
d=int(input("enter a number: "))
avg=(a+b+c+d)/4
print("average of all numbers which you entered:", avg)

# 15.Use the help function to check what the abs function in python does. 
help(abs)
abs(5)
   
# 16.What is the output of this code when run from python interpreter.
print(__name__)

# 17. What is the output of this code when run from a python script. 
#same output as above

# 18.Does the dir of int class contain an attribute __name__ (Y/N).
dir(int)
#ans- no

# 19.Predict the output of: 
print(__name__)
print(__builtins__.__name__)
print(int.__name__)




   
 

