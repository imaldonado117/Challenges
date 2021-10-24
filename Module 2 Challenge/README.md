# VBA Challenge

## Overview of Project

In this project will be refactoring the the current Module 2 solution code. Making it more efficient and capable of handling larger data sets quickly.

### Purpose

The purpose is to expand the original project to analyze the entire stock market over the last few years. However, the current VBA script was not codded to handle the large volume of data. The code needs to be change to efficiently and quickly analyze the entire data set.
## Results

![VBA Challenge 2017](https://github.com/imaldonado117/Challenges/blob/main/Module%202%20Challenge/Resources/VBA_Challenge_2017.PNG) 
![VBA Challenge 2018](https://github.com/imaldonado117/Challenges/blob/main/Module%202%20Challenge/Resources/VBA_Challenge_2018.PNG)

Based upon the data generated for 2017, DQ, SEDG, ENPH, and FSLR have the highest returns. It is noted that WQ isn't traded often as it has the lowest volume at about 36M. The previously mentioned stocks have about average trade volume (214M) except FSLR which has the second highest trade value at 684M. This suggests that DQ stocks were often held for long periods of time to get higher returns while the others were traded very often, possibly for short periods of time, and produced high returns.

Based upon the data generated for 2018, most of previously mentioned high returns stocks have experienced a huge drop in returns (130%-140% decrease on average). DQ, SEDG, and FSLR are currently at a 36.7% average loss in returns. The exception is ENPH which only lost about 40% in return value and maintains a very high return value at about 82%.

## Summary

Some advantages in refactoring code is to improve functionality and increase time efficiency. The improved functionality produces code that is easier to update and improve. Coders can efficiently add new functionality available for users. This reduces the likelihood of errors in the future and simplifies the implementation of new software functionality. This in turn would reduce the time in running the code as well as reduce the time needed to fix errors as there would be less of them. The only disadvantage is having to invest the time to refactor properly without adding too much complexity thus increasing the likely hood of producing errors.

In comparison to the original VBA script, the advantages in refactoring the original Stock Analysis code allowed me to produce tables that analyized the Stock Data Metrics quickly and with equal efficiency. The original code took about half a second to run for each year while the refactoring code took about a 1/20th of the time per year (Please see the image above). The table diplay has a much cleaner value formating which converted the decimal place value to percentages and applied a conditional formating to the values. It took a significant amount of time to ensure the refactoring correctly produced the desire results
