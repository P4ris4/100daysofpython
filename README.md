# 100daysofpython
Code that I wrote and the project that I made during my self taught 100 days of python journey.

First example
print("Hello There")
print("welcome to the band name generator")
city=input("What city did you grew up in?\n")
pet=input("what is the name of your pet?\n")
print("you band name could be " + city + " " + pet)
#--------------------------------------------

#Second example
#Write a program that switches the values stored in the variables a and b
a = input("a: ")
b = input("b: ")
#The process of swapping the values of two variables using a temporary variable (like 'c' in this case) is a common programming technique called "variable swapping" or "value swapping."
c = a
a = b
b = c
#In Python, when we use the " + " symbol with strings (which are basically words or letters), it joins or concatenates them together. So, when we do print("a: " + a), we're telling Python to join the label "a:" and the value of the variable 'a' together. Imagine that 'a' contains the number 10. So, print("a: " + a) will become print("a: " + "10")
print("a: " + a)
print("b: " + b)

#-----------------------------------------------
#Third example
#In this example we are trying to code for adding two numbers together, first we have to set up variables, before that we wanted to check to see what type of data we have so we used type function. after assigning variables, we changed the data type to int in order to add them up. and lastly you print the reslut.
two_digit_number = input("Type a two digit number: ")
first_digit= two_digit_number[0]
second_digit= two_digit_number[1]
result= int(first_digit) + int(second_digit)
print(result)
