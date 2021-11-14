# Academic_Performance_Analysis
Challenge assignment for Module 4

## Background
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

### Overview of the school district analysis: 
The purpose of this analysis is to determine the effects of attempting to correct what may have been record tampering on the score of Thomas High School. At this point in time, the school board has no evidence who altered the scores of Thomas HS's 9th graders and need to determine if whatever alterations took place severely affected Thomas HS's standing in the district.   

### Results: 

#### How is the district summary affected?

As seen below, overall passing scores fell by 0.3%, passing reading scores fell by 0.1%, and passing math scores fell by 0.2%. However, average reading scores did not change while average math scores fell by 0.1%. 


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


The overall passing grades of Thomas High School students dropped from 90.948012% to 65.076453% after replacing THS 9th graders' scores with NaN and rose to 90.630324% after deleting them from THS's data.

The percentages of Thomas High School students passing reading fell from 97.308869 to 69.663609% and rose to 97.018739% after deleting them from THS's data.

The percentages of Thomas High School students passing passing fell from 93.272171% to 66.911315% and rose to 93.185690% after deleting them from THS's data.

The average scores of THS's reading and math did not change that much; while tenths, hundreths, and thousandths of a percentage changed from old, Nan, and deleted scores, both math and reading scores did not drop from about 83%. 


##### School Analysis Before Replacing Altered Scores
![School Analysis Before Replacing Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_Before_NAN.PNG)


##### School Analysis After Replacing Altered Scores
![School Analysis After Replacing Altered Scores with NAN](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_After_NAN.PNG)


##### School Analysis After Deleting Altered Scores
![School Analysis After Deleting Altered Scores](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/THS_School_Summary_No_THS_9th_Graders.PNG)



#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
While replacing the 9th graders' scores with NaN would drop Thomas High School outside of the Top 5 performing schools due to 65.076453% being outside of the Top 5 performing schools, simply deleting it would keep it inside the Top 5 performing schools as it brought the score back to 90.630324%.  


#### How does replacing the ninth-grade scores affect the following:

* ##### Math and reading scores by grade
As seen below, math and reading scores of Thomas High School were not affected aside from the omissions of compromised THS 9th Graders' scores.

###### Math Scores by Grade Before Deleting THS 9th Graders
![Math Scores by Grade Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Math_Scores_Before_NAN.PNG)

###### Math Scores by Grade After Deleting THS 9th Graders
![Math Scores by Grade After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Math_Scores_No_THS_9th_Graders.PNG)


###### Reading Scores by Grade Before Deleting THS 9th Graders
![Reading Scores by Grade Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Reading_Scores_Before_NAN.PNG)

###### Reading Scores by Grade After Deleting THS 9th Graders
![Reading Scores by Grade After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Reading_Scores_No_THS_9th_Graders.PNG)


* ##### Scores by School Spending
As seen below, only the average reading score for the Spending Per Student bin for $601-$650 was affected; rising from 82% to 82.1% when compromised THS 9th Grade scores were omitted. 

* ##### Scores by School Spending Before Deleting THS 9th Graders
![Scores by School Spending Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Spending_Summary_Before_NAN.PNG)

* ##### Scores by School Spending After Deleting THS 9th Graders
![Scores by School Spending After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Spending_Summary_No_THS_9th_Grade.PNG)


* #### Scores by School Size 
As seen below, scores for medium sized schools with 1000 to 2000 students were not affected at all. Thomas High School is a medium sized school with 1635 students. 

* #### Scores by School Size Before Deleting THS 9th Graders
![Scores by School Size Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Size_Summary_Before_NAN.PNG)

* #### Scores by School Size After Deleting THS 9th Graders
![Scores by School Size After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Size_Summary_No_THS_9th_Grade.PNG)


* ##### Scores by School Type 
As seen below, scores for charter schools were not affected at all. Thomas High School is a charter school. 

* ##### Scores by School Type Before Deleting THS 9th Graders
![Scores by school type Before Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Type_Summary_Before_NAN.PNG)

* ##### Scores by School Type After Deleting THS 9th Graders
![Scores by school type After Deleting THS 9th Graders](https://github.com/Itgotworse26/Academic_Performance_Analysis/blob/main/Results/Type_Summary_No_THS_9th_Grade.PNG)


### Summary: 
If the NaN that replaced the scores of Thomas High School's 9th graders were treated as zeros; the effect on Thomas High School's standing within the district would be devaststating. Thomas High School would drop from the Top 5 performing schools in the district, and drag down the performance of schools that spent $601-$650 per student, medium sized schools with 1000 to 2000 students, and charter schools. However, as seen above, if the compromised THS 9th graders were omitted, Thomas High School would stay inside the Top 5 performing schools and the scores of the district would only move a few percentages from the original scores.

The school district shhould take this as an opportunity to ask itself how it would treat the compromised scores and whether they would want to comsider them as zeros or simply omit them as done in the above analysis. While omitting the scores allows the district to maintain its original performance, it still does not answer the how, when, and why the scores of Thomas High School's 9th graders were suspected to be compromised.