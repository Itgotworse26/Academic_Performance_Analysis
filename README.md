# Academic_Performance_Analysis
Challenge assignment for Module 4

## Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Overview of the school district analysis: 
The purpose of this analysis is to determine the effects of attempting to correct what may have been record tampering on the score of Thomas High School. At this point in time, the school board has no evidence who altered the scores of Thomas HS's 9th graders and need to determine if whatever alterations took place severely affected Thomas HS's standing in the district.   

### Results: 

#### How is the district summary affected?

##### District Analysis Before Replacing THS 9th Grade Scores with NAN
![District Analysis Before Replacing THS 9th Grade Scores with NAN](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/District_Summary_Before_NAN.PNG)

##### District Analysis After Replacing THS 9th Grade Scores with NAN
![District Analysis After Replacing THS 9th Grade Scores with NAN](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/District_Summary_After_NAN.PNG)


#### How is the school summary affected?
Please note: the Column Order is: 

School Type	

Total Students	

Total School 

Budget	

Per Student Budget	

Average Math Score	

Average Reading Score	

% Passing Math	

% Passing Reading	

% Overall Passing

##### School Analysis Before Replacing Altered Scores
![School Analysis Before Replacing Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_Before_NAN.PNG)


##### School Analysis After Replacing Altered Scores
![School Analysis After Replacing Altered Scores with NAN](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_After_NAN.PNG)

##### School Analysis After Deleting Altered Scores
![School Analysis After Deleting Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_No_THS_9th_Graders.PNG)



#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


#### How does replacing the ninth-grade scores affect the following:

* ##### Math and reading scores by grade

###### Math Scores by Grade Before Deleting THS 9th Graders
![Math Scores by Grade Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Math_Scores_Before_NAN.PNG)

###### Math Scores by Grade After Deleting THS 9th Graders
![Math Scores by Grade After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Math_Scores_No_THS_9th_Graders.PNG)


###### Reading Scores by Grade Before Deleting THS 9th Graders
![Reading Scores by Grade Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Reading_Scores_Before_NAN.PNG)

###### Reading Scores by Grade After Deleting THS 9th Graders
![Reading Scores by Grade After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Reading_Scores_No_THS_9th_Graders.PNG)


* ##### Scores by School Spending Before Deleting THS 9th Graders
![Scores by School Spending Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Size_Summary_Before_NAN.PNG)

* ##### Scores by School Spending After Deleting THS 9th Graders
![Scores by School Spending After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Spending_Summary_No_THS_9th_Grade.PNG)


* #### Scores by School Size Before Deleting THS 9th Graders
![Scores by School Size Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Size_Summary_Before_NAN.PNG)

* #### Scores by School Size After Deleting THS 9th Graders
![Scores by School Size After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Size_Summary_No_THS_9th_Grade.PNG)


* ##### Scores by School Type Before Deleting THS 9th Graders
![Scores by school type Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Type_Summary_Before_NAN.PNG)

* ##### Scores by School Type After Deleting THS 9th Graders
![Scores by school type After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Type_Summary_No_THS_9th_Grade.PNG)


### Summary: 
If the suspected grades were replaced, the effects on Thomas High School's standings would be large.

* The overall passing grades of Thomas High School students dropped from 90.948012% to 65.076453% after replacing THS 9th graders' scores with NaN and rose to 90.630324% after deleting them from THS's data.

* The percentages of Thomas High School students passing reading fell from to 69.663609% and rose to 97.018739% after deleting them from THS's data.

* The percentages of Thomas High School students passing passing fell from 93.185690% to 66.911315%.

* The average percentages of Thomas High School students' math and reading scores however did not change from 83.350937% or 83.896082% respectively. 

While the average percentages of math and reading scores would not change, the percentages of students passing math, reading, and overall dropped by more than 20%. Also, with the corrections to the grades, Thomas High School would no longer be in the Top 5 schools.