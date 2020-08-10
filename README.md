# School_District_Analysis
Analysis of school district data

## Overview

A school district analysis was conduceted to perform insight on student funding and student standardized test scores to help the school board and superintendent to make effective decisions for school budget allocation. The school board believes there is evidence of academic dishonesty for both reading and math grades for Thomas High School ninth graders. This project is to re-do the school district analysis after setting all 9th grade reading and math scores for Thomas High School to NaNs, and comparing the outcomes.

## Resources

Data source: students_complete.csv; schools_complete.csv

Software: Python 3.7.6, Jupyter Notebooks

## School District Results

How is the district summary affected?

- The district summary was affected in multiple ways. The student counts for passing reading and math scores have changed. Math counts have decreased by 431 students and reading counts have decreased by 452 students.

- The average math score slightly increased by 0.1 in the new analysis. In addition, students that passed math, reading, and overall percentages decreased by 1% each in the new analysis. 

How is the school summary affected?

- In the per school summary table, Thomas High School's average math and reading scores were slightly affected, while the percent of students that passed math, reading, and overall percentages changed dramatically. The percentage of students that passed math decreased by 26.4%, reading decreased by 27.6%, and overall decreased by 25.87%. 

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

- After replacing the ninth graders' math and reading scores, Thomas High School is no longer on the top five performing schools list. 

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade
  
- Thomas High School contains an "nan" in place of where the 9th grade scores would be in the math and reading scores by grade tables.
  
Scores by school spending
  
- One of the spending ranges in the new analysis for overall passing percentages was affected. For the bin range from $630-644, the percent of students that passed math dropped 6%, reading dropped 7%, and the overall passing percentage dropped 7%.

Scores by school size

- For medium size schools, student population from 1000 to 2000 students, the percent of students that passed math dropped 6%, reading dropped 6%, and overall  dropped 6%.

Scores by school type

- Charter school percentages of students that passed math, reading and the overall percent were affected. Math dropped 4%, reading dropped 4%, and the overall percent dropped 3%. 


## School District Summary

After replacing the 9th grade reading and math scores for Thomas High School with NaNs, the school is no longer on the top performing schools list. The percent of students that passed math and reading dropped dramatically, and therefore affected the overall percent. Medium size school results for scores by school size were affected majorily and the scores by school type affected charter school results.


