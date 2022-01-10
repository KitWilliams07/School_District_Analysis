# School_District_Analysis

## Overview of Project 
Prior to the project, a comprehensize School District Analysis was preformed on collected data of school metrics and student performance. The analysis broke down performance of students based on grade and school as well as provided information regarding school spending and size. 

The purpose of this project was to recreate this analysis based on suspicion of academic integrity for the 9th grade reading and math scores for Thomas High School. The project completed below adjusts the analysis by removing the suspected dishonest scores to see how it impacted the School District Analysis.

## Results

Lets first consider the District Summary. Below is the Data Frame created for the initial analysis, including the 9th grade scores from Thomas High School. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/old_district_analysis.png)

Here is the new Data Frame that reflects the adjusted scores. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/new_district_analysis.png)

The total schools, students, and budget did not change since we only adjusted math and reading scores for a select group of stuents. However, this alteration did cause a drop in all of the other metrics. This shows the performance of the students dropped when the 9th grade scores at Thomas High School were not included. 


Looking next at the School Summary metrics, since these metrics are calculated for each school there is going to be no impact on the scores for the other schools. Below is the Data Frame created for this new analysis. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/school_summary.png)

You can find the information on Thomas High School in the 13th row. Within this row, some of the columns involving student budget and student total does not change. However for the reading and math scores, as well the respective % passing scores, this Data Frame shows lower values than the older analysis. This is again because the 9th grade scores were higher, so when they are ignored, the resulting scores will drop. 

## Summary 



After removing the math and reading scores of 9th graders at Thomas High School, the overall performance metrics for the District Summary dropped. This suggests that these students could have been cheating, or they are very smart because they brought up the scores for both subjects. 
