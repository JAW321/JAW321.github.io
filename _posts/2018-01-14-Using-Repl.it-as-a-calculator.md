---
title: Using Repl.it as a calculator
layout: post
author: james.watson
permalink: /using-repl.it-as-a-calculator/
source-id: 1zDOgyqrY85ATxSI6K270KetCg3uGlWRWjzQ3e4Dp_Pc
published: true
---
Date: 8/1/18

Today we were using repl.it to do calculations. To start off we were seeing how you could do basic sums with numbers then changed the numbers to letters.

This can be helpful but for each sum you have to change the numbers which can be more annoying if you are doing complex calculations. From here I added and input option.

def get_user_inputs():

  return int(input("Enter your number"))

By doing this it means the computer will ask the user for two numbers which it will then add to the calculations. After adding all the different operations my code looked like this,

def main():

  while True:

	print("What function would you like to do?")

	choice=input("")

  a=get_user_inputs()

  b=get_user_inputs()

  print (multiplication(a,b))

def get_user_inputs():

  return int(input("Enter your number"))

def addition(a,b):

 return a+b

def subtraction(a,b):	

 return a-b

def multiplication(a,b):  

 return a*b

def division(a,b):  

 return a/b

main()

When the user typed in two numbers it would assign them to a or b and then complete the operation you selected after you answered all the questions with the (inputs).

