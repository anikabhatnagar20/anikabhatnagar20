---
toc: true
comments: false
layout: post
title: College Board Questions MC Correction 
description: This is a reflection on my MC, I am noting down teh specific questions I got wrong and why. 
type: tangibles
courses: { compsci: {week: 11} }
---
# Overall Score: 58/66 
## Question 5 
The ticket prices at a movie theater are given below.

A table is shown with 2 columns and 4 rows. The first row of the table contains the column headers, from left to right, Type of Ticket and Price in dollars. The table is as follows: Regular, 12 Child ages 12 and below, 9 Senior ages 60 and above, 9 Below the table is the text: Additional 5 dollar fee for 3 D movies

A programmer is creating an algorithm to set the value of One word, ticket Price based on the information in the table. The programmer uses the integer  variable age for the age of the moviegoer. The Boolean variable One word, is 3 D is true when the movie is 3-D and false otherwise. 
Which of the following code segments correctly sets the value of One word, ticket Price ?

The block code consists of 5 lines. Some of the lines of code are indented. The code uses the variable ticket Price, closed up with initial capital P, henceforth referred to as ticket Price. Line 1: ticket Price left arrow 12 Begin block Line 2: IF begin block, begin block, age less than or equal to 12, end block, OR, begin block, age greater than or equal to 60, end block, end block Begin block Line 3, indented 1 tab: ticket Price left arrow 9 End block End block Begin block Line 4: IF begin block is 3 D, closed up with numeral 3 and capital D, end block Begin block Line 5, indented 1 tab: ticket Price left arrow 17 End block End block

B
The block code consists of 5 lines. Some of the lines of code are indented. The code uses the variable ticket Price, closed up with initial capital P, henceforth referred to as ticket Price. Line 1: ticket Price left arrow 12 Begin block Line 2: IF begin block, begin block, age less than or equal to 12, end block, OR, begin block, age greater than or equal to 60, end block, end block Begin block Line 3, indented 1 tab: ticket Price left arrow 9 End block Line 4: ELSE Begin block Line 5, indented 1 tab: ticket Price left arrow 17 End block End block

C
The block code consists of 5 lines. Some of the lines of code are indented. The code uses the variable ticket Price, closed up with initial capital P, henceforth referred to as ticket Price. Line 1: ticket Price left arrow 12 Begin block Line 2: IF begin block, begin block, age less than or equal to 12, end block, OR, begin block, age greater than or equal to 60, end block, end block Begin block Line 3, indented 1 tab: ticket Price left arrow 9 End block End block Begin block Line 4: IF begin block is 3 D, closed up with numeral 3 and capital D, end block Begin block Line 5, indented 1 tab: ticket Price left arrow ticket Price plus 5 End block End block

D. 
The block code consists of 5 lines. Some of the lines of code are indented. The code uses the variable ticket Price, closed up with initial capital P, henceforth referred to as ticket Price. Line 1: ticket Price left arrow 12 Begin block Line 2: IF begin block, begin block, age less than or equal to 12, end block, OR, begin block, age greater than or equal to 60, end block, end block Begin block Line 3, indented 1 tab: ticket Price left arrow 9 End block Line 4: ELSE Begin block Line 5, indented 1 tab: ticket Price left arrow ticket Price plus 5 End block End block

## Reflection: 
I chose B, which is incorrect because it applies a ticket price of 17 for all customers aged between 12 and 60 without considering the 3-D aspect of the movie. The code fails to address pricing variations that should exist for 3-D movie screenings. The correct option C because the code segment accurately assigns a base ticket price of 12 and then appropriately adjusts the price to 9 for children and seniors, reflecting age-based discounts. Additionally, it correctly increases the ticket price by 5 for 3-D movies, showing it accounts for different pricing tiers based on movie format.


## Question 7 
Consider the following program, which uses the variables start, end, and current.

The program consists of 7 lines. Begin program Line 1: start, left arrow, 1 Line 2: end, left arrow, 20 Line 3: current, left arrow, 3 Line 4: start, left arrow, current Line 5: current, left arrow, current, plus 1 Line 6: DISPLAY, open parenthesis, start, close parenthesis Line 7: DISPLAY, open parenthesis, current, close parenthesis End program.

What is displayed as a result of executing the program?

A.
1 3
B.
3 3
C.
3 4
D.
4 4

## Reflection 
I chose option A, this option is incorrect because it misrepresents the 'start' and 'current' values as their initial ones when, in fact, they are not the end results after some operation or series of operations has been performed. The final values should reflect the changes that have occurred during the process. The correct option is C which is right because it describes a sequence where the code segment correctly assigns initial values to 'start' (1), 'end' (20), and 'current' (3), and then updates 'start' to 'current's value (3). Subsequently, it increases 'current' from 3 to 4, resulting in the final values of 'start' being 3 and 'current' being 4, as stated.

## Question 10 
The procedure One word, Draw Circle, open parenthesis, x comma y comma r, close parenthesis can be used to draw a circle on a coordinate grid. The circle is centered at the coordinate x comma y and has a radius of runits. The procedure will be used to draw the following figure on a coordinate grid.
The figure shows an x y coordinate plane with 3 circles plotted. Each circle has a radius of 2. 1 circle is centered at the coordinate (3, 6), 1 circle is centered at the coordinate (5, 4), and 1 circle is centered at the coordinate (7, 2).
Which of the following code segments can be used to draw the figure?
A.
The program consists of 8 lines. Begin program Line 1: one word, x Pos, left arrow, 3 Line 2: one word, y Pos, left arrow, 6 Line 3: REPEAT 3 TIMES Line 4: open brace Line 5: one word, Draw Circle, open parenthesis, one word x Pos comma one word y Pos comma 2, close parenthesis Line 6: one word x Pos, left arrow, one word x Pos, plus 2 Line 7: one word y Pos, left arrow, one word y Pos, plus 2 Line 8: close brace End program.
B.
The program consists of 8 lines. Begin program Line 1: one word, x Pos, left arrow, 3 Line 2: one word, y Pos, left arrow, 6 Line 3: REPEAT 3 TIMES Line 4: open brace Line 5: one word, Draw Circle, open parenthesis, one word x Pos comma one word y Pos comma 2, close parenthesis Line 6: one word x Pos, left arrow, one word x Pos, plus 2 Line 7: one word y Pos, left arrow, one word y Pos, minus 2 Line 8: close brace End program.
C.
The program consists of 8 lines. Begin program Line 1: one word, x Pos, left arrow, 7 Line 2: one word, y Pos, left arrow, 2 Line 3: REPEAT 3 TIMES Line 4: open brace Line 5: one word, Draw Circle, open parenthesis, one word x Pos comma one word y Pos comma 2, close parenthesis Line 6: one word x Pos, left arrow, one word x Pos, plus 2 Line 7: one word y Pos, left arrow, one word y Pos, plus 2 Line 8: close brace End program.
D.
The program consists of 8 lines. Begin program Line 1: one word, x Pos, left arrow, 7 Line 2: one word, y Pos, left arrow, 2 Line 3: REPEAT 3 TIMES Line 4: open brace Line 5: one word, Draw Circle, open parenthesis, one word x Pos comma one word y Pos comma 2, close parenthesis Line 6: one word x Pos, left arrow, one word x Pos, plus 2 Line 7: one word y Pos, left arrow, one word y Pos, minus 2 Line 8: close brace End program.

## Reflection

This option A is incorrect because moving "to the right and up" from the original coordinates (3, 6) would not result in the centers of the subsequent circles being at (5, 8) and (7, 10). The pattern suggests a consistent movement of two units to the right and two units up each time, which is not correctly reflected in the given coordinates. Though B is correct because it describes a consistent action where the code segment draws a circle at (3, 6) and then correctly moves to the right by 2 units and down by 2 units to draw the next circles, resulting in the new centers at (5, 4) and (7, 2), respectively. This accurately reflects the described directional changes and distances moved.

## Question 21
The following question uses a robot in a grid of squares. The robot is represented by a triangle, which is initially facing right.

The figure shows a grid of squares with 4 columns and 8 rows. The square in the first row and third column is gray, and all other squares are white. The square in the fourth row and first column contains a right-facing triangle, representing a robot. A path of arrows shows the robot’s movement from its initial location to the gray square. The path shows the robot moving 2 squares to the right from its initial location, then 3 squares up to the gray square.

Consider the procedures below.

The block code consists of 3 lines. Begin block Line 1: PROCEDURE, Move X Times, 1 word with capital M, X, and T, begin block, x, end block Begin block Line 2, indented 1 tab: REPEAT x TIMES Begin block Line 3, indented 2 tabs: MOVE underscore FORWARD End Block End block End block The block code consists of 3 lines. Begin block Line 1: PROCEDURE, Right X Times, 1 word with capital R, X, and T, begin block, x, end block Begin block Line 2, indented 1 tab: REPEAT x TIMES Begin block Line 3, indented 2 tabs: ROTATE underscore RIGHT End block End block End block

Which of the following code segments will move the robot to the gray square?

A.
The block code consists of 3 lines. Line 1: Move X Times, begin block, 2, end block Line 2: Right X Times, begin block, 1, end block Line 3: Move X Times, begin block, 3, end block
B.
The block code consists of 3 lines. Line 1: Move X Times, begin block, 2, end block Line 2: Right X Times, begin block, 3, end block Line 3: Move X Times, begin block, 3, end block
C.
The block code consists of 3 lines. Line 1: Move X Times, begin block, 3, end block Line 2: Right X Times, begin block, 1, end block Line 3: Move X Times, begin block, 3, end block
D.
The block code consists of 3 lines. Line 1: Move X Times, begin block, 3, end block Line 2: Right X Times, begin block, 3, end block Line 3: Move X Times, begin block, 3, end block

## Reflection 
Option A is incorrect because after the robot is rotated to face the bottom of the grid, moving it forward three squares would not correspond with a standard grid's orientation, potentially causing the robot to move off the grid or into an unintended position.This code segment for B is correct because rotating the robot right three times effectively makes it complete a 270-degree turn, which would make it face upwards or towards the top of the grid again. Then, moving it forward three squares aligns with this new orientation, heading towards the top and reaching the specified gray square.

## Question 33
Directions: The question or incomplete statement below is followed by four suggested answers or completions. Select the one that is best in each case.

A flowchart is a way to visually represent an algorithm. The flowchart below is used by an apartment rental Web site to set the variable include to true for apartments that meet certain criteria.

A table is shown with 2 columns and 4 rows. The first row of the table contains the column headers, from left to right, Block and Explanation. The table is as follows: Oval, The start or end of the algorithm. Diamond, A conditional or decision step, where execution proceeds to the side labeled true if the condition is true and to the side labeled false otherwise. Rectangle, 1 or more processing steps, such as a statement that assigns a value to a variable.

The figure shows a flow chart. An oval labeled Start points to a diamond labeled floor greater than 10. The diamond has an arrow labeled false pointing toward another diamond labeled bedrooms equals 3. The second diamond has an arrow labeled false pointing toward a rectangle labeled include left arrow false. Both diamonds have arrows labeled true pointing toward a rectangle labeled include left arrow true. Both rectangles point to an oval labeled End.

Which of the following statements is equivalent to the algorithm in the flowchart?

A.
Include, left arrow, open parenthesis, floor greater than 10, close parenthesis, OR, open parenthesis, bedrooms equal 3, close parenthesis
B.
Include, left arrow, open parenthesis, floor greater than 10, close parenthesis, AND, open parenthesis, bedrooms equal 3, close parenthesis
C.
Include, left arrow, open parenthesis, floor less than or equal to 10, close parenthesis, OR, open parenthesis, bedrooms equal 3, close parenthesis
D.
Include, left arrow, open parenthesis, floor less than or equal to 10, close parenthesis, AND, open parenthesis, bedrooms equal 3, close parenthesis

## Reflection 
Option B is incorrect because the expression is meant to set "include" to true only when both conditions—floor being greater than 10 and bedrooms equaling 3—are met simultaneously. However, the given logic does not address scenarios where "include" should be true if only one of the conditions is met, which suggests a logical OR should be used instead of an AND. The correct answer would be option A because the flowchart sets include to true whenever floor is greater than 1 0 or bedrooms equal 3, and sets include to false otherwise. Therefore, the algorithm is equivalent to     Include, left arrow, open parenthesis, floor greater than 10, close parenthesis, OR, open parenthesis, bedrooms equal 3, close parenthesis.

## Question 46 

A student wants to create an algorithm that can determine, given any program and program input, whether or not the program will go into an infinite loop for that input.

The problem the student is attempting to solve is considered an undecidable problem. Which of the following is true?

A. 
It is possible to create an algorithm that will solve the problem for all programs and inputs, but the algorithm can only be implemented in a low-level programming language.
B. 
It is possible to create an algorithm that will solve the problem for all programs and inputs, but the algorithm requires simultaneous execution on multiple CPUs.
C. 
It is possible to create an algorithm that will solve the problem for all programs and inputs, but the algorithm will not run in reasonable time.
D. 
It is not possible to create an algorithm that will solve the problem for all programs and inputs.

## Reflection 
B is wrong because it is not possible to create an algorithm to solve an undecidable problem for all programs and inputs. So then D is correct. Just to clairfy because an undecidable problem is one in which no algorithm can be constructed that always leads to a correct yes-or-no answer.

## Question 60 
Which of the following are ways in which a programmer can use abstraction to manage the complexity of a program?

Select two answers.

A.
Replacing each instance of repeated code with a call to a procedure
B.
Replacing longer variable names with shorter variable names to reduce typing errors
C.
Replacing several lines of documentation with a single line of documentation
D.
Replacing several lines of documentation with a single line of documentation One word, name 1, One word, name 2, One word, name 3, and One word, name 4 with a list of strings
called names

## Reflection 
This question involved me picking 2 answers. I got one option correct, A. Instead of C which is wrong because  Placing all documentation in a single line does not help a programmer to manage the complexity of a program. D would be teh correct second option since Creating a list of names is an example of a data abstraction that may make it easier for a programmer to manage the complexity of a program.

## Question 64 
Which of the following statements describe how cloud computing has affected Internet communication?

Select two answers.

A.
Cloud computing has eliminated the need to provide redundancy in Internet routing.
B.
Cloud computing has helped enhance collaboration.
C.
Cloud computing has introduced new data-security concerns.
D.
Cloud computing has reduced concerns about intellectual property rights.

## Reflection 
Again this is a 2 answer question. I got B correct though instea of D which is wrong because cloud storage sites allow users to share files easily, which could lead to increased concerns about copyrighted materials being illegally distributed online. The correct second option would be C since cloud computing sites must consider security concerns in order to protect their users’ private data.
