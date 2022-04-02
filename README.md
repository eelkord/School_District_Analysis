# School_District_Analysis

## A written Report for the School District Analysis





****Overview of the school district analysis:


****The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help

We want to see now how removing test results from Thomas High School’s grade 9 class will affect the overall results which was obtained in the assessment in Module 4



#Result/Analysis:

Initially we covered all school grades of reading and math at Thomas High School for the ninth grade by replacing the scores to NaN

We used the loc method to identify those values and then replace them.
 
![image](https://user-images.githubusercontent.com/100106554/161361476-db15cdca-07cf-474d-86fe-a8cffa5473b9.png)

We were able to count 461 students

And the total of students not including Thomas High School grade 9 was 38709



##Next:
The School District Analysis
In this section, we reanalyzed the following metrics after excluding the 9th-graders test results:
•	The district summary
•	The school summary
•	The top 5 and bottom 5 performing schools, based on the overall passing rate
•	The average reading score for each grade level from each school
•	The average math score for each grade level from each school
•	The scores by school spending per student, by school size and by school type

Recalculated the passing math and passing reading percentage and overall passing percentage

 ![image](https://user-images.githubusercontent.com/100106554/161361494-f04f0034-5258-4d9c-9bb4-58971a8cd067.png)-	How is the district summary affected?
o	The overall Passing Percentage for both math and reading was 64.86%
o	Passing Math percentage became 74.8%

-	How is the school summary affected?
Using the same method from previous examples, created school type, total students, Total School Budget, Per Student Budget, Average Math Score, Average Reading Score, % Passing Math, %Passing reading and the % overall Passing
 
 ![image](https://user-images.githubusercontent.com/100106554/161361507-5cbf9a2b-74a6-46f3-b3ca-eed84d307292.png)

 
 
 
Thomas High School Overall Passing Percentage went down to 65% after removing the 9th grade testing
-	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Math became 99.9% as oppose to 93.27% before
And reading become 69.66% from 97.31% before
-	How does replacing the ninth-grade scores affect the following:

o	Math and reading scores by grade – Math for 9th grade went from 83.27% to 80.12% and reading did not change
o	Scores by school spending

![image](https://user-images.githubusercontent.com/100106554/161361526-e2511d69-dbbd-4792-8e8a-56c309a28484.png)


Score by school spending went to $630 to $644 for the overall passing score of 64%
o	Scores by school size
 
 ![image](https://user-images.githubusercontent.com/100106554/161361537-91fe1d69-c3d1-498f-a14a-7ef0efacbf6a.png)

 
Thomas High School is in the medium range
o	Scores by school type
 ![image](https://user-images.githubusercontent.com/100106554/161361548-94d7be0a-ab9d-4430-93a4-af604c210b75.png)

Summary:

Overall, replacing all of Thomas High School’s grade 9th math and reading results with Nan has negatively affected the data frame. Thomas High School overall percentage of passing students dropped from 2nd to 8th. And affected the charter schools and sized in the range of 1000 to 2000 kids
