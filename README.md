# Academic_Performance_Analysis
Challenge assignment for Module 4

## Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Overview of the school district analysis: 
The purpose of this analysis is to determine the effects of attempting to correct what may have been record tampering on the score of Thomas High School. At this point in time, the school board has no evidence who altered the scores of Thomas HS's 9th graders and need to determine if whatever alterations took place severely affected Thomas HS's standing in the district.   

### Results: 

#### How is the district summary affected?

##### District Analysis
![District Analysis](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/District_Summary.PNG)


#### How is the school summary affected?

##### School Analysis Before Replacing Altered Scores
![School Analysis Before Replacing Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/per_school_summary_df_Altered.PNG)


##### School Analysis After Replacing Altered Scores
![School Analysis After Replacing Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/per_school_summary_df_Correct.PNG)


#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
#### How does replacing the ninth-grade scores affect the following:

* ##### Math and reading scores by grade

###### Math scores by grade
![Math scores by grade](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Math_Scores_by_Grade.PNG)

###### Reading scores by grade
![Reading scores by grade](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Reading_Scores_by_Grade.PNG)

* ##### Scores by school spending
![Scores by school spending](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Scores_by_Spending.PNG)

* ##### Scores by school size
![Scores by school size](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Scores_by_Size.PNG)

* ##### Scores by school type
![Scores by school type](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Scores_by_Type.PNG)

### Summary: 
If the suspected grades were replaced, the effects on Thomas High School's standings would be large.

* The overall passing grades of Thomas High School students dropped from 90.630324% to 65.076453%.

* The percentages of Thomas High School students passing reading fell from 97.018739% to 69.663609%.

* The percentages of Thomas High School students passing passing fell from 93.185690% to 66.911315%.

* The average percentages of Thomas High School students' math and reading scores however did not change from 83.350937% or 83.896082% respectively. 

While the average percentages of math and reading scores would not change, the percentages of students passing math, reading, and overall dropped by more than 20%. Also, with the corrections to the grades, Thomas High School would no longer be in the Top 5 schools; its place would be taken by Wright High School. 