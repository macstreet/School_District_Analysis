# School District Analysis
## Overview
An analysis of school district and student data was performed by first importing the data into a DataFrame using Pandas. The data was then prepared and cleaned by removing missing (NaN) values, removing duplicate rows, and adjusting the data types as needed - in this case, "grade" was changed from an object to an integer. The student DataFrame was then broken out into summary statistics using the `describe` function. The mean math score was pulled as well as the minimum reading score. 

More specific data analysis was performed using the `loc` function. Using `loc` and `describe` the summary statistics of students in the 9th grade were generated. Along with other statistics, the average reading score of all students in 11th and 12th grade is generated using the `loc` function as well.

Finally, the data is compared utilizing the `groupby` function. Average budgets between public and charter schools are compared. The total number of students at each school is generated, and that list is sorted into descending order. Finally, average math scores are compared between grades and school types. 


## Summary
For summary of analysis findings, refer to last cell in `Student_Data_Challenge_Code.ipynb`
