# 4.9 Summing
# Introduction
In this lesson, students will learn about summing using a for loop. 
# Learning Target
The students will be able to use a for loop with a sum variable to sum a set of variables

# Components:

# Lesson Practice
Remember!  The order of your code is very important inside of a loop. If you find that the output is off a little, but the code looks correct, trace through the code and you may see that some lines of code just need switched or moved around.

Notice that before the for loop begins, the sum variable is set to 0. This is called initializing the variable. The variable (sum) is set to a known value (0) before the variable’s value changes inside the loop.

# Code Practice 
A for loop can be used to sum a list of numbers. For example, this program:

sum = 0

for i in range (2, 6):
    
    sum = sum + i

print(str(sum))

adds 2 + 3 + 4 + 5 and prints: 14

>>>.
The order of your code is very important inside of a loop. If you find that the output is off a little, but the code looks correct, trace through the code and you may see that some lines of code just need to be switched or moved around.

When using a sum variable, it normally is initialized to 0 before the loop begins. If you do not first initialize it as something, how can you add to it?

A variable is initialized whenever it is first assigned a value. However, you cannot use a variable on the right side of an assignment without it first being assigned a value. Ex: x = input(“Name: “) is fine to use even if x is not yet defined, because it is on the left side of the assignment. Ex: x = 4 * r is not okay if r has not yet been initialized - how can I multiply by something I do not know the value of?

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3A-AP-18
