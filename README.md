# PandaChallenge
Purpose of Project
In this assignment, you'll create and manipulate Pandas DataFrames to analyze school and standardized test data. This assignment is applying concepts that I learned in pandas units.

PyCitySchools
In this challenge, you are tasked to use Pandas and Jupyter Notebook to create a report that includes the following data with a written description of at least two observable trends based on data. The followings need to be created:

District Summary
Create a high-level snapshot, in a DataFrame, of the district's key metrics, including the following:
Total schools
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
School Summary
Create a DataFrame that summarizes key metrics about each school, including the following:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Highest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the top 5 performing schools based on % Overall Passing. Include the following metrics:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Lowest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the bottom 5 performing schools based on % Overall Passing. Include the following metrics:
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Math Scores by Grade
Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Scores by School Size
Create a table that breaks down school performance based on school size (small, medium, or large).
Scores by School Type
Create a table that breaks down school performance based on type of school (district or charter).
The purpose of this challenge is to create a report using Pandas and Jupyter Notebook with data to compare the school budgets, school size, school types, and number of students for the school board and mayor to make strategic decisions on the future school budgets and prioities.

Analysis
By analyzing the report, followings found:

Charter School has the higher passsing rate on both math and reading than district school, which made charter school's overall passing rate higher as well. The overall passing rate for Charter school is 90.4% whereas 53.7% for district school.
Small (<1000) and medium (1000-2000) school size has the similar(only few decimal points different) passing rate on math, reading and overall. Both school size have overall passing rate at 89%~90.6% whereas Large (2000-5000) school size has 58.3%.
School with the lowest spending range per student buget (<$585) shows the highest on overall including scores and rate. School with the highest spending ($645-680) shows the lowest overall score and rate.

Recommandation
From this challenge and analysis, I can recommend the school board and mayor that it is better to limit the school sizes to less than 1000 or in between 1000-2000 to have overall math and reading rate to high 80s and low 90s. From this analysis, we can find school spending range per student doesn't equal to the overall rate since the higher spending schools have the lowest scores and rate. This concludes, Charter school's score and rate is better than district school and budget doesn't have high effects on the rate and score but the school size does.
