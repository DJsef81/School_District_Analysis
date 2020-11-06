# School_District_Analysis

# Overview of the school district analysis:
We were tasked with assisting Chief Data Scientist Maria of City School District. Her job consists of preparing all standardized tests data for analysis to inform discussions and strategize decisions at the school and district level by looking for performance trends and patterns in the data. 

We analyzed student funding and student standardized test scores, then aggregated the data and showcased trends in school performance in order to assist the school board and superintendent in making their decisions on where to prioritize funding with their budget. 

However, after we had concluded our analsis, we were informed that The school board had notified Maria and her supervisor that the students_complete.csv file which we used in our analysis, showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 

Maria asked us to take out the 9th grade math and reading scores for Thomas High School while keeping the rest of the data intact. After we replaced the math and reading scores, we repeated the school district analysis and this is our report to describe how these changes affected the overall analysis, if at all.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.7, Jupyter Notebook 6.1.4

# Results 

## School Summary Before Removing THS 9th Grade Scores
![](/Analysis/per_school_summary_1.png)

## School Summary After Removing THS 9th Grade Scores
![](/Analysis/per_school_summary_2.png)

## District Summary Before Removing THS 9th Grade Scores
![](/Analysis/district_summary_1.png)

## District Summary After Removing THS 9th Grade Scores
![](/Analysis/district_summary_2.png)

## Math Scores Before Removing THS 9th Grade Scores
![](/Analysis/math_scores_by_grade_1.png)

## Math Scores After Removing THS 9th Grade Scores
![](/Analysis/math_scores_by_grade_2.png)

## Reading Scores Before Removing THS 9th Grade Scores
![](/Analysis/reading_scores_by_grade_1.png)

## Reading Scores After Removing THS 9th Grade Scores
![](/Analysis/reading_scores_by_grade_2.png)

## Top 5 Schools Before Removing THS 9th Grade Scores
![](/Analysis/top_schools_1.png)

## Top 5 Schools After Removing THS 9th Grade Scores
![](/Analysis/top_schools_2.png)

## Bottom 5 Schools Before Removing THS 9th Grade Scores
![](/Analysis/bottom_schools_1.png)

## Bottom 5 Schools After Removing THS 9th Grade Scores
![](/Analysis/bottom_schools_2.png)

## Scores by School Type Before Removing THS 9th Grade Scores
![](/Analysis/by_type_1.png)

## Scores by School Type After Removing THS 9th Grade Scores
![](/Analysis/by_type_2.png)

## Scores by School Spending Before Removing THS 9th Grade Scores
![](/Analysis/spending_ranges_1.png)


## Scores by School Spending Before Removing THS 9th Grade Scores
![](/Analysis/spending_range_2.png)






## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade

Examining the math and reading score by grade, all the schools remained unaffected except of course the Thomas High School ninth grade scores which returned a NaN value.

### Scores by school spending

The score by school spending remained unchanged when rounded (Less than 1% change).
Scores by school size

The score by school size remained unchanged as well when rounded (Less than 1% change).
Scores by school type

The score by school type remained unchanged as well when rounded (Less than 1% change).

# Summary:

Removing the math and reading scores for the 9th graders of Thomas High School did not significantly effect our analysis. Some of the major changes we saw were;

% Passing Math for Thomas High School went from 66.90 to 93.18
% Passing Reading for Thomas High School  went from 69.65 to 97.02
% Passing Overall for Thomas High School went from 65.08 to 90.63
When examing the overall district summary, the average scores and % passing went down by less than .05%

