Readme

//////////////////////////////////////////////////////////////////////////////////////////
Arab Academy for Science and Technology - CCIT
CS143-Problem Solving 7th assessment 
//////////////////////////////////////////////////////////////////////////////////////////
Written by: Mark Tharwat Samir Tawfik
Teacher : Nagy K. Aly
//////////////////////////////////////////////////////////////////////////////////////////
This code is a retail sales analysis application that performs the following functions: 
1.	Allows the user to enter the sales data for all branches and for all months and store them in single data structure.
2.	Allows user to add a new branch or delete an existing branch record
3.	Calculate the total sales of the company.
4.	Calculate the percentage share of each branch in the total sales.
5.	Determine the month of the peak sales.
6.	Allows the user to specify a certain month, and in response the program displays the list of branch indices sorted in a descending order based on the sales revenue.
7.	Allows the user to specify a certain branch, and in response the program displays the list of months indices sorted in a descending order based on the sales revenue.
8.	Allows the user to choose the functionality he wishes to make use of.  The user should be prompted with a question if he wishes to continue or not. The program should terminate if the user does not want to continue.
//////////////////////////////////////////////////////////////////////////////////////////
number of branches: 3

sales for 3 branches:

sales for branch 1:
sales for month 1: 275
sales for month 2: 134
sales for month 3: 475
sales for month 4: 396
sales for month 5: 246
sales for month 6: 77
sales for month 7: 63.5
sales for month 8: 98
sales for month 9: 365
sales for month 10: 446
sales for month 11: 491
sales for month 12: 431

sales for branch 2:
sales for month 1: 218
sales for month 2: 40
sales for month 3: 199
sales for month 4: 279
sales for month 5: 325
sales for month 6: 175
sales for month 7: 407
sales for month 8: 427
sales for month 9: 471
sales for month 10: 125
sales for month 11: 334
sales for month 12: 464

sales for branch 3:
sales for month 1: 456
sales for month 2: 215
sales for month 3: 151
sales for month 4: 418
sales for month 5: 465
sales for month 6: 274
sales for month 7: 81
sales for month 8: 392
sales for month 9: 265
sales for month 10: 445
sales for month 11: 200
sales for month 12: 54

SAMPLE OUTPUT:

Functionality #1:

Branch\Month:   1        2      3       4       5        6       7      8       9      10       11      12
Branch 1:	275.0   134.0   475.0   396.0   246.0    77.0    63.5    98.0   365.0   446.0   491.0   431.0
Branch 2: 	218.0    40.0   199.0   279.0   325.0   175.0   407.0   427.0   471.0   125.0   334.0   464.0
Branch 3: 	456.0   215.0   151.0   418.0   465.0   274.0    81.0   392.0   265.0   445.0   200.0    54.0
 
Functionality #2: branch 4 added

Branch\Month:   1        2      3       4       5        6       7      8       9      10       11      12
Branch 1:	275.0   134.0   475.0   396.0   246.0    77.0    63.5    98.0   365.0   446.0   491.0   431.0
Branch 2: 	218.0    40.0   199.0   279.0   325.0   175.0   407.0   427.0   471.0   125.0   334.0   464.0
Branch 3: 	456.0   215.0   151.0   418.0   465.0   274.0    81.0   392.0   265.0   445.0   200.0    54.0
Branch 4: 	786.0   210.0   201.0   518.0   765.0   267.0    90.0   792.0   216.0   435.0   500.0   345.0

Functionality #3: branch 4 deleted

Branch\Month:   1        2      3       4       5        6       7      8       9      10       11      12
Branch 1:	275.0   134.0   475.0   396.0   246.0    77.0    63.5    98.0   365.0   446.0   491.0   431.0
Branch 2: 	218.0    40.0   199.0   279.0   325.0   175.0   407.0   427.0   471.0   125.0   334.0   464.0
Branch 3: 	456.0   215.0   151.0   418.0   465.0   274.0    81.0   392.0   265.0   445.0   200.0    54.0

Functionality #4:

Total Company Sales = 10377.5

Functionality #5:

Branch 1 shares = 33.7%
Branch 2 shares = 33.4%
Branch 3 shares = 32.9%

Functionality #6:

Month 9 has the peak sales of 1101.0

Functionality #7: 

Input 2
Month 2 sales:
Branch 3: 215.0
Branch 1: 134.0
Branch 2: 40.0

Functionality #8:
 
Input 2
Branch 2 sales:
Month 9: 471.0
Month 12: 464.0
Month 8: 427.0
Month 7: 407.0
Month 11: 334.0
Month 5: 325.0
Month 4: 279.0
Month 1: 218.0
Month 3: 199.0
Month 6: 175.0
Month 10: 125.0
Month 2: 40.0
//////////////////////////////////////////////////////////////////////////////////////////
