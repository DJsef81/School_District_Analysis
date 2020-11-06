# School_District_Analysis

# Overview of the school district analysis:
We were tasked with assisting Chief Data Scientist Maria of City School District. Her job consists of preparing all standardized tests data for analysis to inform discussions and strategize decisions at the school and district level by looking for performance trends and patterns in the data. 

We analyzed student funding and student standardized test scores, then aggregated the data and showcased trends in school performance in order to assist the school board and superintendent in making their decisions on where to prioritize funding with their budget. 

However, after we had concluded our analsis, we were informed that The school board had notified Maria and her supervisor that the students_complete.csv file which we used in our analysis, showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. 

Maria asked us to take out the 9th grade math and reading scores for Thomas High School while keeping the rest of the data intact. After we replaced the math and reading scores, we repeated the school district analysis and this is our report to describe how these changes affected the overall analysis, if at all.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.7, Jupyter Notebook 6.1.4

# Results of Analysis Both Before and After Removing Thomas High School (THS) 9th Grade Scores

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

# Results From Removing THS 9th Grade Scores
Comparing the results shown above, we see in the following areas:

### District Summary
  * The percentage passing math went down from 75% to 74.8%.
  * The percentage passing reading went down from 86% to 85.7%.
  * The overall passing percentage went down from 65% to 64.9%. 

### School Summary 
  * For Thomas High School:
    * The average math score decreased from 83.41 to 83.35. 
    * The average reading score increased from 83.84 to 83.89.
    * The percentage passing math decreased from 93.27% to 93.18%.
    * The percentage passing reading decreased from 97.30% to 97.01%
    * The percentage overall passing decreased from 90.94% to 90.63%. 

### THS Performance Realative to the other Schools
  * THS is still the second highest performing school behind Cabrera High School. 
  
### Math and Reading Scores by Grade
  * THS 9th Grade scores for reading and math replaced with a "Nan" value. 
  
### Scores by School Spending
  * No significant change
  
### Scores by School Size
  * No significant change
  
### Scores by School Type
  * For Charter Schools 
      * The average math score decreased from 83.47 to 83.46
      * The average reading score increased from 83.89 to 83.9
      * The percentage passing math score decreased from 93.62% to 93.61%.
      * The percentage passing reading score decreased from 96.58% to 96.55%.
      * The percentage overall passing score decreased from 90.43% to 90.39%. 
      
# Summary:

Removing the math and reading scores for the 9th graders of Thomas High School did not significantly effect our analysis. Some of the changes we saw were:

* In our District Summary:
  * The percentage passing math went down 0.2%.
  * The percentage passing reading went down 0.3%.
  * The overall passing percentage went down 0.1%. 

* In our School Summary, Thomas High School had the most obvious changes as they were the school mainly affected from the changes. Those changes were:
  * The average math score decreased by 0.06.
  * The average reading score increased by 0.05.  
  * The percentage passing math decreased by 0.09%. 
  * The percentage passing reading decreased by 0.29%.
  * The percentage overall passing decreased by 0.31%. 

* For Scores by School Type, charter school scores were affected as follows:
  * The average math score decreased by 0.01. 
  * The average reading score increased by 0.01. 
  * The percentage passing math score decreased by 0.01%.  
  * The percentage passing reading score decreased by 0.03%.
  * The percentage overall passing score decreased by 0.04%.

Again, most changes were not very significant in that they did not highly impact our analysis. 

However, looking at the bottom 5 performing schools, we can see that they are all District Schoools, and are are in the School Size Large (2000 to 5000 students).

In comparison, the top 5 performing schools are all Charter Schools, with only Wilson high being in the School Size Large category. 

When comparing the average amount spent per student of the top 5 and bottom 5, the bottom 5 schools actually spend $40.20 more than the top 5. It stand to reason that School Size and type of school is factor in scores, although there is probably many other factors that contribute to their performance that are not present in this analysis. 
