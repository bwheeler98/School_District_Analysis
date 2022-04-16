# School_District_Analysis
## Resources
- Data Source: schools_complete.csv & students_complete.csv
- Python & Jupyter Notebook

## Project Overview
The purpose of this project was to analyze two large datasets in order to breakdown the data and format it into a more presentable format that is easier to read and analyze.  The first dataset analyzed was information about each school in the scholl system.  The other dataset analyzed was comprised of individual student data from each school and how well they did on their math and reading tests.  There was an error with the 9th grade students' test scores from Thomas High School, so the first step was to replace these false scores from our data with "NaN" so that the analysis would be more accurate.  We then created various dataframes to analyze the passing percentage at each school based on size, type of school, and spending per student.   

## Results
District Summary w/out 9th grade THS scores:
- The percentage of students passing math decreased slightly from 75% to 73.9%
- The percentage of students passing reading decreased slightly from 86% to 84.7%
- The overall percentage of passing students decreased slightly from 65% to 64.1%

![Screen Shot 2022-04-15 at 9.28.13 PM.png](https://github.com/bwheeler98/School_District_Analysis/blob/7ea67ae2dcd34543a2084a6377aa41a1718130b9/Images/Screen%20Shot%202022-04-15%20at%209.28.13%20PM.png)

Thomas High School w/out 9th grade scores:
- The percentage of students passing math decreased greatly from 93.3% to 66.9%
- The percentage of students passing reading decreased greatly from 97.3% to 69.7%
- The overall percentage of passing students decreased greatly from 90.9% to 65.1%

![Screen Shot 2022-04-15 at 9.39.47 PM.png](https://github.com/bwheeler98/School_District_Analysis/blob/7ea67ae2dcd34543a2084a6377aa41a1718130b9/Images/Screen%20Shot%202022-04-15%20at%209.39.47%20PM.png)

## Summary
The 9th grade math scores for Thomas High School were high which elavated the passing math percentage for that school.  You can conclude that the 9th grade math scores were high because once they were removed the passing math percentage decreased greatly.  You can also condlude that the 9th grade reading scores were high because once they were removed the passing reading percentage decreased greatly.  With the combination of these two aspects the overall passing percentage decreased greatly for Thomas High School.  
