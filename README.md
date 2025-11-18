The local hospital allows outpatients to take a blood test and it wants to make a basic graphical
display (histogram) to show how many patients took the test in various age groups in a day. You are
required to write a program in C++ that achieves this. The program consists of the following three
tasks:

Task 1: The program should allow the hospital administrator to enter the age of each outpatient
who visited the hospital for a blood test on a particular day (assuming that only one visit per
day is allowed), until the administrator enters the age exceeding 109.
At this point the program should display a histogram using a symbol exclamation mark (!).
Each ‘!’ represents the outpatient’s age range as shown below.
You will find an example of the program output below. The example below shows the
distribution of ages for 30 outpatients.
Example output:
0-19 !!!!!
20-39 !!!!!!!
40-69 !!!!!
70-89 !!!!!!!!!!!
90-109 !!
• Your program should work with any number of outpatients visiting the hospital in one day.
• As the administrator enters each ‘age’, a counter should count the number of ages which
have been entered per patient.
2 | P a g e
You should use five groups only: 0-19,20-39,40-69,70-89,90-109 for age
range
• Make sure the display is neatly formatted as in the example output above.
• Your program should make use of ‘loops’ for the display of each age group.

Task 2: After the histogram, a variety of statistics should be displayed such as: total number of
outpatients visited in a day, total number of patients in a day who are below the age of 40,
the highest and the lowest age of patients visited the hospital in a day.

Task 3: According to task 1, the histogram shows each age group horizontally across the screen.
Now change your solution to display the histogram vertically.
Copy your original solution, rename it and make changes to the new solution to display the
histogram vertically. This means that the exclamation mark (!) in an age group should go
downwards and not across the screen.
