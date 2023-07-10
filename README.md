# pandas-challenge
---
In this challenge, I'll be helping the school board and mayor make strategic decisions regarding future school budgets and priorities.
## Summary
---
The analysis focuses on analyzing school and student data to generate key metrics and insights. 
This is a summary of what I did in this analysis.

### District Summary:

The District Summary contains the following data:

1. Total Schools: Total number of schools in the district.
2. Total Students: Total students in the district.
3. Total Budget: The total budget for the district.
4. Average Math Score: The average math score across all students in the district.
5. Average Reading Score: The average reading score across all students in the district.
6. % Passing Math: Percentage of students passed the math exam.
7. % Passing Reading: Percentage of students passed the reading exam.
8. % Overall Passing: Percentage of students passed both math and reading.

### School Summary:

This is the representation of data for each school in the district, including the following data:

1. School Type: The school type for each school.
2. Total Students: Each school has a total of students.
3. Total School Budget: The total budget for each school.
4. Per Student Budget: The budget per student for each school.
5. Average Math Score: The average math score for each school.
6. Average Reading Score: The average reading score for each school.
7. % Passing Math: Percentage of students in each school passed the math exam.
8. % Passing Reading: Percentage of students in each school passed the reading exam.
9. % Overall Passing: Percentage of students in each school passed both math and reading.

**Using the above data, I was able to extract the following information:**

- Highest-Performing Schools (by % Overall Passing):
    The top 5 highest-performing schools based on % Overall Passing are [list of top performing schools].

- Lowest-Performing Schools (by % Overall Passing):
    The bottom 5 lowest-performing schools based on % Overall Passing are [list of bottom performing schools].

- Math Scores by Grade:
    The average math scores for students in each grade (9th, 10th, 11th, 12th) are as follows:
        - 9th Grade: [average math score for 9th graders]
        - 10th Grade: [average math score for 10th graders]
        - 11th Grade: [average math score for 11th graders]
        - 12th Grade: [average math score for 12th graders]

- Reading Scores by Grade:
    The average reading scores for students in each grade (9th, 10th, 11th, 12th) are as follows:    
    - 9th Grade: [average reading score for 9th graders]
    - 10th Grade: [average reading score for 10th graders]
    - 11th Grade: [average reading score for 11th graders]
    - 12th Grade: [average reading score for 12th graders]

- Scores by School Spending:
    The analysis categorizes schools into spending ranges per student:
    - <$585
    - $585-630
    - $630-645
    - $645-680
    The average math and reading scores, % passing math, % passing reading, and % overall passing for each spending range are calculated and presented in the table.

- Scores by School Size:
    The analysis categorizes schools into size ranges:
    - Small (<1000)
    - Medium (1000-2000)
    - Large (2000-5000)
    The average math and reading scores, % passing math, % passing reading, and % overall passing for each size range are calculated and presented in the table.

- Scores by School Type:
    The analysis groups schools by their type (District or Charter).
    The average math and reading scores, % passing math, % passing reading, and % overall passing for each school type are calculated and presented in the table.

## Conclusion
---
By looking at the analysis results, I was able to draw the following conclusions:

- School Spending: By looking at the spending summary table, the data shows that more spending has no impact on overall passing percentage. Actually, the data shows that schools with the lowest spending range has the highest overall passing percentage, and the schools with the highest spending range has the lowest overall pass percentage, which may show bad allocation of resources at the higher spending schools.

- School Size: From the school size summary table, we can see that the overall passing percentage for small and medium sized schools is around 90%, but when we look at the overall passing percentage for large schools it is only **58.29%**, which may give us an insight about the bad impact of having large number of students in the same school on their scores. Also if you look at the highest performing schools and the lowest performing schools tables, you will find that the top five performing schools three of them is medium, one small and one large while if you look at the bottom five performing schools, you will find that all of these schools are large sized.

- School Type: From the school type summary table, we can see that the overall passing percentage in charter school **90.43%** is much higher than the overall passing percentage in district schools **53.67%**, also if you look at the highest performing schools and the lowest performing schools tables, you will find that the top five performing schools are all charter schools and the bottom five performing schools are all district schools, that also may go back to the school size as most of the charter schools are medium and small sized.

- The last conclusion is by looking at the the math score and reading score by grade tables for each school you will find that the scores are mostly consistent for all grades at the same school, which means that the performance of the students at each school does not change much over grades.
## Source Code
---
- counting the number of unique values <https://practicaldatascience.co.uk/data-science/how-to-identify-and-count-unique-values-in-pandas>
- To get unique values from multiple columns <https://favtutor.com/blogs/pandas-unique-values-in-column>
- grouping and counting <https://sparkbyexamples.com/pandas/pandas-groupby-count-examples/?expand_article=1>
- how to extarct 1D array from tuples <https://www.geeksforgeeks.org/how-to-extract-a-particular-column-from-1d-array-of-tuples/>
- Python lambda <https://www.geeksforgeeks.org/python-lambda/>
- Replacing a piece of string <https://sparkbyexamples.com/pandas/pandas-replace-substring-in-dataframe/?expand_article=1>
- FutureWarning: The default value of regex will change from True to False in a future version <https://stackoverflow.com/questions/66603854/futurewarning-the-default-value-of-regex-will-change-from-true-to-false-in-a-fu>

## References
Data generated by [Mockaroo, LLCLinks](https://mockaroo.com/), (2022). Realistic Data Generator. Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

