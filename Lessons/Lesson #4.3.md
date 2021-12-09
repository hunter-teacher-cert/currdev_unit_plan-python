# 4.3 Two Ways to End a Loop
# Introduction
This lesson introduces two ways to end a loop: using a count variable to run a loop a specific number of times, and using user input. 

# Learning Target
The students will be able to end loops using count variables and user input and be able to state when to use them.

# Components:

# Lesson Activities
While loops end when their condition becomes False. The condition could be anything, but two useful patterns for how we use the conditional in a while loop are ending it based on user input and ending based on some count variable.

Looping based on a count variable lets us run the while loop block a specific amount of times.

While loops end when their condition becomes False. The condition could be anything, but two useful patterns for how we use the conditional in a while loop are ending it based on user input and ending based on some count variable.

Looping based on a count variable lets us run the while loop block a specific amount of times.

# Code Practice Example 1:
c = 0

while (c < 7):
    
    c = c + 1
    
    print("Python")

This prints Python 7 times.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>.

We can also end a loop based on user input:

# Code Practice Example 2: 
n = int(input("enter #'s, -1 to stop"))

sum = 0

while (n != -1):
    
    sum = sum + n
    
    n = int(input ("enter #'s, -1 to stop"))

print("Total: " + str(sum))

The loop will continue summing numbers until the user has entered -1, at which point the loop will end.

>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>.

Just like when using strings in my control expression, or a user input variable, any variable, including the count variable must change inside the loop in order for the loop to eventually end.
A while loop can run an indefinite amount of times by gathering user input or it can run a set amount of times by controlling it with a count variable.

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3A-DA-12
