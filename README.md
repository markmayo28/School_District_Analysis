# City School Analysis

## Project Overview

The city school district initially asked us to review standardized test scores across the city schools to look for trends in test results based on several factors:

1. How does school size effect test scores.
2. How does the school budgets effect test scores.
3. How does school type effect test scores.

## Resources

- Data Source: election_results.csv (provided by the Colorado Board of Elections)
- Software: Python 3.9.4, Jupyter Notebook 6.3.0

## Summary

At a glance, the below chart shows a summary of school testing data by school. Deeper analysis will follow, but this chart provides some good high-level insight into the testing data by school.

![Testing_School_Summary](https://user-images.githubusercontent.com/78807451/119065862-81e95c80-b9ac-11eb-8f11-2b9185209750.png)

## Factor Analysis

### Test Scores by School Size

For size comparison schools were broken down into groups of small (less than 1000 students), medium (1000-2000 students), and large (2000-5000 students). Analysis indicates that the small and medium schools performed significantly better than the large schools in standardized testing success.

![Test_Scores_size](https://user-images.githubusercontent.com/78807451/119065899-988fb380-b9ac-11eb-9880-4bdbe48cfff9.png)

### Test Scores Based on Per Student Budget

For spending comparison schools were broken into four groups based on the amount each school spends per student each year. This figure was derived by dividing the total school budget by the number of students. Counter intuitively, the schools spending less money per student tended to perform better. This may be explained further down as we explore school type.

![Test_Scores_Spending](https://user-images.githubusercontent.com/78807451/119065995-c248da80-b9ac-11eb-85bb-c7552191e3d7.png)


### Test Scores Based on School Type

The final break down was based on school type. The city has two types of schools: District and Charter. The Charter schools performed significantly better on standardized testing that their District counter parts, despite spending less money per student.

![Test_Scores_Type](https://user-images.githubusercontent.com/78807451/119066010-cecd3300-b9ac-11eb-843a-48e7a54efc3e.png)


## Additional Anaysis

After the initial analysis was complete the city schools district realized that there was evidence of academic dishonesty. Specifically, the test results for Freshman at Thomas High School appeared to have been altered. While the investigation is still ongoing, the school district would like the scores in question removed from the analysis and understand how the impact this has on the overall results.

### Factors Analyzed After Removing Thomas High School Freshmen Results

1.  District Summary

The District Summary was basically unaffected by removing the Thomas High School freshman results. This is due to the fact that there were only 461 test scores removed from the overall total, which is only about 1% of the total. Passing percentage went up .2% on Math, .1% on Reading, and .3% Overall.

District Summary After Removing THS Freshman
<img width="949" alt="District_Summary" src="https://user-images.githubusercontent.com/78807451/119232296-af402280-baf2-11eb-8929-afc058849460.png">

Original District Summary
<img width="927" alt="New_District_Summary" src="https://user-images.githubusercontent.com/78807451/119236489-b6bcf700-bb05-11eb-99b0-3edd84fb0ae7.png">

2.  School Summary 
Analysis of the school summary shows that Thomas High School showed a very slight increase in average math (up .18) and reading (up .07), as well as a very slight increase in passing percentage. Math passing percentage was up almost .1%, reading was up just under .3%, and over all passing was up just over .3%.

School Summary After Removing THS Freshman
<img width="986" alt="New_School_Summary" src="https://user-images.githubusercontent.com/78807451/119237432-c7bc3700-bb0a-11eb-95e9-b91d6fa8f970.png">

Original School Summary
<img width="995" alt="School_Summary" src="https://user-images.githubusercontent.com/78807451/119237442-d3a7f900-bb0a-11eb-9bb8-39cfd5f826d8.png">

3. Thomas High School Performance Relative to Other Schools in the District

While removing the freshman test scores did show a slight increase in passing average scores and passing percentage, there was no change in Thomas High School's ranking among district schools. Thomas High School remains in second place behind Cabrera High School.  The chart below shows the top five schools in the district based on standardized testing performance.

<img width="995" alt="Top Schools" src="https://user-images.githubusercontent.com/78807451/119237599-a3148f00-bb0b-11eb-959a-5d2b38337ce3.png">

4. Math and Reading Scores by Grade

Analysis indicates that standardized testing scores by grade were not affected, since we only removed freshman scores from Thomas High school and this was a statistically insignificant sample.

Math and Reading Scores by Grade Respectively

<img width="318" alt="Math_Scores_by_Grade" src="https://user-images.githubusercontent.com/78807451/119238236-5337c700-bb0f-11eb-91ea-caeea28c387e.png">  <img width="328" alt="Reading_Scores_by_Grade" src="https://user-images.githubusercontent.com/78807451/119238241-5df25c00-bb0f-11eb-87c0-765e7562c67b.png">

5. Scores by School Spending

There was no noticable change in the statistics based on school spending. Basing average scores to one-tenth of a point and averages to the whole number, the removal of the Thomas High School freshmen did not affect the scores. This indicates that any change was less than 0.5%.

![New_Test_Scores_Spending](https://user-images.githubusercontent.com/78807451/119238458-626b4480-bb10-11eb-8695-99acca47a6ee.png)

6. Scores by School Size

There was no noticable change in the statistics based on school size. Basing average scores to one-tenth of a point and averages to the whole number, the removal of the Thomas High School freshmen did not affect the scores. This indicates that any change was less than 0.5%.

![New_Test_Scores_Size](https://user-images.githubusercontent.com/78807451/119238549-f63d1080-bb10-11eb-8504-3fdba359bd0e.png)

7. Scores by School Type

There was no noticable change in the statistics based on school type. Basing average scores to one-tenth of a point and averages to the whole number, the removal of the Thomas High School freshmen did not affect the scores. This indicates that any change was less than 0.5%.

![New_Test_Scores_Type](https://user-images.githubusercontent.com/78807451/119238571-2c7a9000-bb11-11eb-8f3f-a5638ee7b4ad.png)

##Summary of Findings After Removing Thomas High School Freshman Test Scores

Final analysis of the standardized testing data for the school district after removing the Thomas High School freshmen data indicates some minor changes to the original results:

-	Test data for the district showed an increase in passing percentage of 0.2% in the math portion of the standardized test.
-	Test data for the district showed an increase in passing percentage of 0.1% in the math portion of the standardized test.
-	These increases resulted in an overall passing increase of 0.3% across the district
-	Removal of the freshman test data resulted in an increase to average math scores of 0.18 points for Thomas High School.
-	Removal of the freshman test data resulted in an increase to average reading scores of 0.18 points for Thomas High School.
-	Removal of the freshman test data resulted in an increase to average math scores of 0.18 points for Thomas High School.
-	Removal of the freshman test data resulted in an increase to passing percentage at Thomas High School. Math passing percentage was up almost 0.1%, reading was up just under 0.3%, and over all passing was up just over 0.3%.
