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

1.	District Summary

The District Summary was basically unaffected by removing the Thomas High School freshman results. This is due to the fact that there were only 461 test scores removed from the overall total, which is only about 1% of the total. Passing percentage went up .2% on Math, .1% on Reading, and .3% Overall.

District Summary After Removing THS Freshman
<img width="949" alt="District_Summary" src="https://user-images.githubusercontent.com/78807451/119232296-af402280-baf2-11eb-8929-afc058849460.png">

Original District Summary
<img width="927" alt="New_District_Summary" src="https://user-images.githubusercontent.com/78807451/119236489-b6bcf700-bb05-11eb-99b0-3edd84fb0ae7.png">
