# School_District_Analysis
 
## Overview
This analysis of a school district's standardized test scores was requested in order to make strategic decisions regarding the school district. Primary areas of focus are individual school performance, scores based on school spending, scores based on school size, and scores based on school type (charter or district). Unfortunately, after the initial analysis was done, it was discovered that there were students at a particular school who were suspected of illegitimate test scores, and those scores had to be thrown out for the analysis to be repeated. This is a summary of how the results were impacted by removal of those student's test scores.

## Results

* How is the district summary affected?
    * The district summary, which has a row for each student in the district, was impacted because the reading and math scores have been removed from the data frame for Thomas High School 9th Graders.
    
![alt text](https://github.com/XZandermarsh/School_District_Analysis/blob/main/Resources/district_summary_NaN.png "District Summary Updated")

* How is the school summary affected?
    * The school summary was affected for Thomas High School because the math and reading score averages decreases, as well as the % passing for math, reading, and overall. Percentage of students passing math went from 93.27% to 93.19%. Reading decreased from 97.31% to 97.02%. Overall decreased from 90.95% to 90.63%.
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    * While the % changes may seem small, they actually caused Thomas High School to drop in ranking for % of students passing reading from #1 to #3. The rankings for math and overall were not affected by the change.
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
        * Math and reading scores by grade were only impacted for Thomas High School 9th grade results, which were eliminated entirely due to the removal of the students.
        ![alt text](https://github.com/XZandermarsh/School_District_Analysis/blob/main/Resources/grade_summary_math_NaN.png "Grade Summary Updated")
    * Scores by school spending
        * Scores by school spending were marginally affected by the change for the $630-644 range, decreasing from 73.48% to 73.46% for math, 84.39% to 84.31% for reading, and 62.86% to 62.78% for overall passing percentages.
    * Scores by school size
        * Scores by school size were marginally affected by the change for the medium size, decreasing from 93.60% to 93.58% for math, 96.79% to 96.73% for reading, and 90.62% to 90.56% for overall passing percentages.
    * Scores by school type
        * Scores by school type were marginally affected by the change for Charter, decreasing from 93.62% to 93.61% for math, 96.59% to 96.55% for reading, and 90.43% to 90.39% for overall passing percentages.
## Summary:
1. The most significant change for the overall analysis is the change in ranking for reading test results for Thomas High School. Prior to the change, they had the highest passing % for the reading test in the entire district. After the removal of illegitimate scores, they dropped to #3, behind Griffin High Scool and Cabrera High School.
2. Another notable change was on the grade level analysis, because there was no longer a data point for Thomas High School 9th grade. Instead, the summary showed 'NaN' for the average math and reading pass percentages.
3. Scores by school spending decreased slightly for the $630-644 range, but not enough to change the clear negative correlation between spending and test results. Before and after the change, it is apparent that more spending per student does not directly lead to better test results.
