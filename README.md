# Functions
"""
# Python functions:
funtion is a block of code it is executed when it is called in python to create a function "def" key word is used
Syntax : def functionname()
            statement/functin body
        function calling()
"""
 
def meghana(): #functiondefination
    print("good day")
meghana()

#NOTE: 1.The value that was passed into function defination is called parameters.
      #2.The value that was passed into function calling is called arguments
 # passingparameters and arguments
def function(a): #parameter
    print("this is a value:",a)
function(100) #function calling

#Single parameter function : Passing a one or single parameter to a function is called Single parameter
def function2(c): #parameter
    print(c)
function2(926)

#Multiple parameter: Passing a multiple values to a function is called as Multiple parameter function
def function3(a,b):
    print(a+b)
function3(36,45)
# TASK: perform a float division operator for multiple parameter
#2. Write a program to wish a person using a python function
#give a short note on python functions

def function4(a):
    print("Wish you many more happy returns of the day:",a)
function4("Priya")

def function5(a,b):
    print(a/b)
function5(7,2)

#Arbitary argument():
       #Arbitary argument is an argument which is denoted by"*"
       #which takes multi arguments for a single parameter and returns in the form of tuple 
def function6(*a):
    print(a)
function6(10,15,20)

#Key args() Arguments:
#It is a function which takes single parameter for multiple argument in the form of key value pairs. So, the output is in dictionary format.
def function7(**name):
    print("hi",name)
function7(name="meghana",place="kry")
