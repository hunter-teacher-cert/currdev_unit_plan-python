4.1 Loops
# Introduction
In this lesson, students learn about loops. 
The students will:
Be able to define and code while loops and loop control variables 
Components:
Video Lesson
Lesson Practice
Code Practice
What to Emphasize:
The loop control variable must have an opportunity to be changed in a while loop in order for the while loop to end. If the control variable never changes, the loop will be infinite.
The formatting for a while loop is the same as an if statement, where there needs to be a colon after the condition and the code to be executed should be indented underneath.
Additional Notes:
The Viz Mode can be beneficial to help students see how a variable changes throughout a program. This helps them trace through the program and identify where an error may have occurred.

# Lesson Activities

When we want to run some code over and over again, we can use loops.

One type of loop is the while loop. It's a bit like a repetitive if statement: it uses boolean conditions just like the if statement does, but it keeps checking the condition over and over again to verify that it should run the True block.

Example:
name = input("Enter a name, STOP to end")
while (name != "STOP"):
    print("You entered: " + name)
    name = input("Enter a name, STOP to end")
print("Done.")
We first ask for a name, and store it as the variable name. Next, we have a while loop. The while loop first checks if name is something other than "STOP" using !=, a relational operator. (Need to review other relational operators? Return to Lesson 3.2 - Simple Ifs).

This while condition is important here. It lets Python know that the while loop should run only when the condition is True (when name does not equal "STOP"), and that the loop should stop when the condition is False (when name equals "STOP"). It's important that the condition we choose can eventually be False. If we were to write a condition that would never be False (for example, while "string" == "string"), we would create an infinite loop, and the while loop would never end.

If the condition is True (if name is something other than "STOP"), Python will run the code inside the loop, which includes asking for another name. It will then store this new name in the variable name. Afterwards, it'll go back to the original while condition, check the new name against "STOP", and repeat the process over and over until name != "STOP", and the loop will end.


If you'd like to customize the lesson slides, click here.
Curricular Standards
This lesson adheres to the following CSTA Standards: 3B-AP-14




