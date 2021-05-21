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

1.	Test Scores by School Size

For size comparison schools were broken down into groups of small (less than 1000 students), medium (1000-2000 students), and large (2000-5000 students). Analysis indicates that the small and medium schools performed significantly better than the large schools in standardized testing success.

![Test_Scores_size](https://user-images.githubusercontent.com/78807451/119065899-988fb380-b9ac-11eb-9880-4bdbe48cfff9.png)

2.	Test Scores Based on Per Student Budget

For spending comparison schools were broken into four groups based on the amount each school spends per student each year. This figure was derived by dividing the total school budget by the number of students. Counter intuitively, the schools spending less money per student tended to perform better. This may be explained further down as we explore school type.

![Test_Scores_Spending](https://user-images.githubusercontent.com/78807451/119065995-c248da80-b9ac-11eb-85bb-c7552191e3d7.png)


3.	Test Scores Based on School Type

The final break down was based on school type. The city has two types of schools: District and Charter. The Charter schools performed significantly better on standardized testing that their District counter parts, despite spending less money per student.

![Test_Scores_Type](https://user-images.githubusercontent.com/78807451/119066010-cecd3300-b9ac-11eb-843a-48e7a54efc3e.png)


## Additional Anaysis

Colorado Board of Elections asked us to further analyze the election data to determine:

1. The voter turnout for each county
2. The percentage of votes from each county and of the total count.
3. The county with the highest turnout.

## Summary of Results

The analysis of the county data shows that:

- There were three counties included in the election results:
  - Jefferson
  - Denver
  - Arapahoe

- The results by county were:
  - Jefferson county with 38,855 voters which was 10.5% of the overall turnout.
  - Denver county with 306,055 voters which was 82.8% of the overall turnout.
  - Arapahoe county with 24,801 voters which was 6.7% of the overall turnout.

- Denver county had far and away the highest voter turnout with over four times the number of voters than the other two counties combined.

## Audit Summary

The programming script used in this analysis is very versatile and can be adjusted to meet future vote counting needs. The programming script can easily be modified to match with a larger number of counties to include a statewide election. Along the same lines it can also be changed to recognize different candidates and a larger candidate pool. This script will also prove useful to compare election turnout and results across multiple election years. We hope you will find this information meets your needs and will think of us for future projects.

