# EXCEL


https://excel-practice-online.com/


LEARN AND Practice Excel. 
In order to reference a specific cell in Excel, we will type its column letter, followed by the row number. 

So, A1 will be the first cell in your worksheet – It’s in the first column (A), and in the first row (1):



Excel Range

The Excel Range is comprised of two or more adjacent cells. These cells can be in the same row, the same column, or even in multiple rows and columns! 

Each range is represented by two cells – The top-left cell, and the bottom-right cell, separated with colons. 

Excel Worksheet

The Excel Worksheet is comprised of rows and columns. 

The default Excel Worksheet contains 1,048,576 rows and 16,384 columns. 
---------------------------------------------------------------------------------------



=SUM(A1:A6)
\
=MIN(A1:A6)
\
=MAX(A1:A6)
\
=AVARAGE(A1:A6)
\
=MEAN(A1:A6)
\
=MEDIAN(A1:A6)
\
=MODE(A1:A6)
\
=COUNT(A1:A6)
\ 
(count is used to count Numeric values)

COUNT function does not count empty lines
\
=COUNT(A1:F7)
\

=COUNTA(A1:A6)

\ 

(iF ITS Text ,COUNTA is used)

\
Grandpa John gives his kids Christmas gifts, but only if they are younger than 18.

Use IF function to check who’s eligible for Christmas gifts this year. Return “Yes” if he’s eligible, and “No” if he is not.
\
=IF(B3<18,"YES","No")

\

    =SUMIF(range,criteria,[sum_range])

\
--------------------------------------------
Instructions: create a nested if formula where:							
1. Conditions:							
First condition Full-Time							
Second condition GPA Greater than 4.5							
2. Results:							
Gets a discount – return “Yes", otherwise “No"	

\





\
The following formula is a great example of how to use Nested If in this case. 							
=IF(B9="Full-Time",IF(B10>4.5,"Yes","No"),"No")							
Alternatively, you could switch between the first and the second conditions:							
=IF(B10>4.5,IF(B9="Full-Time","Yes","No"),"No")							
There are many other ways you could test 2 or more conditions! We believe that the two examples above are the easiest =)							
	------------------------
