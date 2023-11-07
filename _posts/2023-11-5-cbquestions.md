---
toc: true
comments: false
layout: post
title: College Board Questions MC Correction 
description: Darts game
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