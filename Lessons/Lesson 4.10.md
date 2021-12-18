# 4.10 Review of Algorithms and Tracing
# Introduction
This lesson recalls the lesson on algorithms and code tracing from Unit 3. 
# Learning Target
The students will be able to define algorithms and code tracing and be able to explain techniques for tracing code, and successfully trace code to determine behavior and outputs. 
# Components:

# Lesson Practice 
In order to understand what is happening in a specific algorithm or program, we trace the code and follow each variable and track how that variable is changing and what it should be doing. Adding comments into the code to help explain what each step is doing can be helpful during code tracing Additional Notes: Even though we are trying to “break” our code with different input values, at this point in time, students do not know how to properly make code work if they enter a string when an integer is expected or a float when an integer is expected. However, if we are expecting a string, checking to make sure a single word works, two words, long and short words, no words, etc.

An algorithm is an ordered list of instructions that solves a problem. They are finite processes and they produce a result.

Tracing code means simulating the execution of the code by hand in order to verify it works correctly before it runs. Being able to read and understand a program (either written by you or someone else) is an important skill, especially for beginner programmers.

To trace code, first write down any variable names and their initial values. Then, go through the program line-by-line and write down changes to the variables’ values. As you go, fix any issues in the code.

Tracing code is one of the best ways to double-check your work and spot potential errors. As you step through each line of code, try to “break” the code by testing a variety of values that might cause unintended results.

# Code Practice
. Write down variable names

● Plug in initial values

● Go through each line of code and write down changes to the variables’ values

● Fix any issues in the code, and repeat as needed

total_sum = 0

for i in range (1, 11):
 
 if (i % 2 == 0):
 
  total_sum = total_sum + i

print(total_sum)

Will print - (2+4+6+8+10) = 30 
# Curricular Standards 
This lesson adheres to the following CSTA Standards: 3A-CS-03
