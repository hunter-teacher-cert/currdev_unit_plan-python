# 4.8 Counting by Other Than 1
# Introduction
This lesson explores how a for loop uses parameters to count by numbers other than 1. 

# Learning Target:

The students will be able to code for loops with control variables that increase or decrease by amounts other than 1

# Components:

# Lesson Practice
Remember there are two ways to end a loop: either when user input meets a test condition or when a count variable reaches a limit. A for loop may include user input, but look carefully at what actually stops the loop. Is it what the user inputs? Or does the loop control variable reach its stopping point?

# Code Practice #1:
The for loop can use multiple parameters in the range function.

for i in range(1, 10, 3):
    
    print(i, end=" ")

prints - 1 4 7

# Code Practice #2:

for i in range(12, 2, -3):
    
    print(i, end=" ") 

prints - 12 9 6 3

# Code Practice #3: 
A for loop requires fewer lines of code than a while loop. Here is an example of a while loop and a for loop that perform the same function:

x = 0 

while (x <= 17): 
    
    print(x)
    
    x = x + 2

for x in range(0, 18, 2):
    
    print(x)

Both will print - 0 2 4 6 8 10 12 14 16

Although a for loop will run a set amount of times, you are still allowed to get user input inside of the loop.
Typically a for loop looks neater in a program because it requires a few less lines of code.

A for loop in other languages like C++ or Javascript look slightly different: for( i = 0; i < 10; i + 2). Even though this looks different, the parts of the for loop are the same. There is a starting point (i = 0), and ending point (i < 10) and how we count (i+2).

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3A-AP-18
 
