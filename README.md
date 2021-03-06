# School_District_Analysis

## Overview of Project 
Prior to the project, a comprehensize School District Analysis was preformed on collected data of school metrics and student performance. The analysis broke down performance of students based on grade and school as well as provided information regarding school spending and size. 

The purpose of this project was to recreate this analysis based on suspicion of academic integrity for the 9th grade reading and math scores for Thomas High School. The project completed below adjusts the analysis by removing the suspected dishonest scores to see how it impacted the School District Analysis.

## Results

### District Summary
Lets first consider the District Summary. Below is the Data Frame created for the initial analysis, including the 9th grade scores from Thomas High School. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/old_district_analysis.png)

Here is the new Data Frame that reflects the adjusted scores. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/new_district_analysis.png)

The total schools, students, and budget did not change since we only adjusted math and reading scores for a select group of stuents. However, this alteration did cause a drop in all of the other metrics. This shows the performance of the students dropped when the 9th grade scores at Thomas High School were not included. 


### School Summary 
Looking next at the School Summary metrics, since these metrics are calculated for each school there is going to be no impact on the scores for the other schools. Below is the Data Frame created for this new analysis. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/school_summary.png)

You can find the information on Thomas High School in the 13th row. Within this row, some of the columns involving student budget and student total does not change. However for the reading and math scores, as well the respective % passing scores, this Data Frame shows lower values than the older analysis. This is again because the 9th grade scores were higher, so when they are ignored, the resulting scores will drop. 

### Thomas High School Performance

Below is a Data Frame showing the Top 5 performing schools based on Overall Passing %, prior to ignoring the select students' scores. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/old_thomas_performance.png)

Based on this you can see that Thomas High School ranked 2nd in Overall Passing %. 

Below is a Data Frame showing the Top 5 performing schools AFTER igrnoing the select students' scores. 

![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/new_thomas_performance.png)

From these 2 Data Frames you can see that Thomas High School remains in the 2nd spot in terms of school performance. The Data Frame coming from removing the 9th grader's scores shows that the the % passing for math, reading, and overall all dropped slightly compared to the first Data Frame. However, it was not enough to change them out of the 2nd spot. 

### Math and Reading Score by Grade

Below is the Data Frame for the math scores by grade after adjusting the 9th grade scores for Thomas High School. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/math_score_by_grade.png)

Below is the Data Frame for the reading scores by grade after adjusting the 9th grade scores for Thomas High School. 
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/read_score_by_grade.png)


From these Data Frames, it is clear that setting the 9th graders at Thomas High School scores to NaN should have no effect on the scores of other grades at other schools. These 2 Data Frames show that the math and reading scores for the 9th grade at Thomas High School are set to NaN. 

### Scores by School Spending, Size and Type

Below are the Data Frames that reflect the average scores based on School Spending, School Size, and School Type 

![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/school_spending.png)
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/school_size.png)
![alt text](https://raw.githubusercontent.com/KitWilliams07/School_District_Analysis/main/Resources/school_type.png)


These Data Frames are exactly the same for both analysis, including and excluding the 9th graders' scores. This is due to the shear number of students in the district. These final statisitcs consider entire schools of students rather than grades. As a result, if you exclude a small subset of scores,the overall scores for the whole district will remain virtually unchanged. If the Data Frame displayed the values to more decimal places, it would be easier to see a difference. However rounding to 1 decimal place makes it impossible to see a difference. 

## Summary 

After removing the math and reading scores of 9th graders at Thomas High School, the overall performance metrics for the District Summary dropped. This provides evidence that these students could have been cheating, however based on the data it is impossible to say for ceratin. 

So the changes that occured when setting the 9th grade scores to NaN resulted in a decrease in the following District Metrics...
- Average Math Score
- Average Reading Score
- % Passing Math 
- % Passing Reading
- $ Overall Passing


