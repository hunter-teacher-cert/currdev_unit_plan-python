# 4.1 Loops

# Learning Target: 

The students will be able to define and code while loops and loop control variables 

# Components:

## Lesson Activities

When we want to run some code over and over again, we can use loops.

One type of loop is the while loop. It's a bit like a repetitive if statement: it uses boolean conditions just like the if statement does, but it keeps checking the condition over and over again to verify that it should run the True block.

## Code Practice Example:

name = input("Enter a name, STOP to end")

while (name != "STOP"):
    
    print("You entered: " + name)
    
    name = input("Enter a name, STOP to end")

print("Done.")

We first ask for a name, and store it as the variable name. Next, we have a while loop. The while loop first checks if name is something other than "STOP" using !=, a relational operator. (Need to review other relational operators? Return to Lesson 3.2 - Simple Ifs).

This while condition is important here. It lets Python know that the while loop should run only when the condition is True (when name does not equal "STOP"), and that the loop should stop when the condition is False (when name equals "STOP"). It's important that the condition we choose can eventually be False. If we were to write a condition that would never be False (for example, while "string" == "string"), we would create an infinite loop, and the while loop would never end.

If the condition is True (if name is something other than "STOP"), Python will run the code inside the loop, which includes asking for another name. It will then store this new name in the variable name. Afterwards, it'll go back to the original while condition, check the new name against "STOP", and repeat the process over and over until name != "STOP", and the loop will end.

# Curricular Standards
This lesson adheres to the following CSTA Standards: 3B-AP-14




