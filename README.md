
------------------------------------------------------------------------
------------------------        LICENSING        ------------------------
------------------------------------------------------------------------

MIT License

Copyright (c) 2025 

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.

------------------------------------------------------------------------
------------------------       PYTHON BASICS      ------------------------
------------------------------------------------------------------------

-- INPUTS --

# Ask the user to type something
user_input = input("Say something: ")

if user_input == "hello":
    print("hi!")
else:
    print("bye.")

# Using elif (else + if) for multiple choices
user_input = input("Say hi or bye: ")

if user_input == "hi":
    print("hello!")
elif user_input == "bye":
    print("goodbye!")
else:
    print("I don't understand.")


-- PRINTING & VARIABLES --

# Integer variable (number)
age = 21
print(age)
print("You are " + str(age) + " years old.")

# String variable (text)
name = "Bro Code"
print("Hello, " + name + ".")

# f-strings (better way to print variables)
name = "Dexter"
print(f"Hello, {name}.")

# Float variable (decimal)
height = 5.9
print(f"You are {height} feet tall.")

# Boolean variable (True or False)
is_cool = True
print(f"Are you cool? {is_cool}")


-- DELAYS --

import time

print("Leaving in 3 seconds...")
time.sleep(3)
print("Left.")


-- EXITING THE PROGRAM --

# Option 1: Using os (forceful exit)
import os
# os._exit(0)  # Uncomment to exit immediately

# Option 2: Using sys (graceful exit)
import sys
# sys.exit()  # Uncomment to exit safely


-- EXTRA TIPS --

# You can comment code using # for one line
# or use triple quotes (''' or """) for multi-line comments

# Use type() to check the type of a variable
print(type(age))     # <class 'int'>
print(type(name))    # <class 'str'>
print(type(is_cool)) # <class 'bool'>

# You can get input as a number too:
number = int(input("Enter a number: "))
print(f"Your number times 2 is {number * 2}")
