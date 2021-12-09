# 4.2 Count Variables
# Introduction
This lesson builds on students’ knowledge of loops, and introduces count variables, which help keep track of how many times a loop has run.

## Learning Target: 
The students will bee able to define initializing and be able to define and code the count and sum variables.

# Components:

## Lesson Activities
A count variable must be initialized before using it throughout the program. Most other variables are initialized or set when we get the input from the user, but a count variable is not a user input, so we must initialize it ourselves.
Whenever you are altering a variable, like sum or count, by building off of its current value, the variable appears on both sides of the assignment operator. The alteration to the variable is done on the right side.

Sometimes we want to know more than just what happens in a single iteration of a loop. We might want to know how many times a loop has gone through, or we might want a running sum of some numbers that we put into a loop. We can do that by having a variable outside the loop and changing it (such as by increasing or decreasing it) in each iteration.

## Code Practice Example 1: Count Variable (c)
name = input("STOP to end: ")

c = 0

while (name != "STOP"):
    
    print("You entered: " + name)
    
    name = input("STOP to end: ")
    
    c = c + 1

print("You entered " + str(c) + " words.")

## Code Practice Example 2: Sum Variable (sum)
n = int(input("Enter a number, -1 to stop: "))

sum = 0

while (n != -1):
    
    sum = sum + n 
    
    print("You entered: " + str(n))
    
    n = int(input("Enter a number, -1 to stop: "))

print("Sum of numbers entered: " + str(sum))

## Code Practice Example 3:
count = count - 1

sum = sum + number

answer = answer / 4

duplicate = duplicate * 2

Counting and summing are very common in programs, so instead of having to use the syntax mentioned above to edit a variables current value there is something called shorthand notation. We can instead use something like this: count += 1 or sum += number. Whenever a math symbol appears right before the assignment operator, Python knows to take the variable on the left and perform the operation with the variable on the right and then assigns it back to the variable on the left. 

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3A-AP-18
