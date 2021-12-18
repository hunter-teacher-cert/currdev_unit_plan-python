4.6 Range Function
# Introduction
This lesson introduces a new function, the range function, which returns a set of numbers based on the parameters provided.

# Learning Target 
The students wil be able to define and utilize the range function using 1, 2, or 3 parameters.

# Components:

## Learning Activities

# Lesson Practice

The range function returns a set of numbers based on the information, or parameters, provided. For example, the parameter in range(8) is 8.

print(8) would print a number: 8

print(list(range(8))) would print a list: [0, 1, 2, 3, 4, 5, 6, 7]

In the example above, notice that printing range(8) returns a list of numbers, rather than a single number. Also notice that the list of numbers goes from 0 to 7, or '0' to 'parameter-1'.

A range function can take either 1, 2, or 3 parameters:

range(x) returns numbers from 0 to x-1. For example, range(4) returns a list of numbers from 0 to 3: [0, 1, 2, 3]

range(x,y) returns numbers from x to y-1. For example, range(2, 8) returns a list of numbers from 2 to 7: [2, 3, 4, 5, 6, 7]

range(x, y, z) returns numbers from x to y-1 counting by z. For example, range(9, 0, -2) returns a list of every other number between 9 to 1, including both 9 and 1: [9, 7, 5, 3, 1]

# Code Practice #1

Range (X) - Returns numbers from 0 to x-1

print(range(15))

● Returns: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14]

# Code Practice #2

Range (X, Y) - Returns numbers from x to y-1

print(range(2,8)

● Returns: [2, 3, 4, 5, 6, 7]

# Code Practice #3

Range (X, Y, Z) - Returns numbers from x to y-1 counting by z

print(range(9,0,-2))

range (x, y, z)

● Returns: [9, 7, 5, 3, 1]

>>>.

The range function can be used in a for loop in order to determine not only how many times a program will run, but which values will be stored to the i variable. Ex: for i in range(1, 10, 2) would run 5 times, and would store the values of 1, 3, 5, 7, and 9 to i each time through the loop.

Range can be used to count up, count down and to count by different amounts besides 1 at a time.

Although you will frequently see the range function used with a for loop, there are other applications of the range function as well.

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3A-AP-21

