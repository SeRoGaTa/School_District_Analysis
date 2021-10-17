# School District Analysis

***Version 1.0.0***

---

## Overview of School District Analysis
#### Maria, a coworker, requested this analysis where we can see a first glance, how several schools have scored in math and reading assignments, this analysis will deliver a high-level summary of school’s grades (averages of Math and Reading signatures scores and their percentages of approval rate) as well as type, size and budget grouping tables.

#### Specifically, this analysis will deliver the following metrics:
1. District summary DataFrame
2. School summary DataFrame
3. Top 5 and bottom 5 performing schools based in overall passing rate
4. Average of math and reading scores by grade
5. And math and reading scores by grouping size, type and budget schools.

Also, after having evidence of a dishonesty grades for Thomas High School 9th grade, we include into this report two sets of metrics, the first one excluding data from Thomas High School 9th grade and the following with a complete set of data so the end user can see the difference between both.

## Analysis results:
#### Here I'll show how the metrics got affected after replacing Thomas High School 9th grade scores with Nan's.

- How is the district summary affected?
  -  As you can see in the images below, we have a minor drop (since we aren't using too many decimals) on the math and reading percentage scores and a 0.1 % reduction in the overall score after droping the 9th grade scores for the Thomas High School. 
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/district_summary2.png" width="800">
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_district_summary2.png" width="800">
- How is the school summary affected?
  -  Once we split the summary by schools, we can see a bigger drop in the assignments and overall percentage scores, we are seeing in the following images if we focus on the Thomas High School row a .25 average drop in their values for the percentages.
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Schools_district_summary.png" width="800">
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_schools_district_summary.png" width="800">
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  -  After droping those scores, we see that Thomas High School besides we can see a drop of 0.31% in their overall percentage scores, it remains as the second better school of the district. 
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Schools_district_sortedup.png" width="800">
  <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_schools_district_sortedup.png" width="800">
- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Here is simple to see the changes in math and reading scores divided by grades. Because we drop all 9th grade scores you will see in the following images that for the Thomas High School and 9th grade the values changed to a NaN but the rest of the table remains intact.       
    - Math<img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Per_schools_math_grades.png" width="300">          <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_per_schools_math_grades.png" width="300">
    - Reading<img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Per_schools_reading_grades.png" width="300">          <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_per_schools_reading_grades.png" width="300">

-  Scores by school spending
      -  Since the affected scores were not that large against the complete data set, we barely see a minor drop in the decimals on 630-640 row.
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Per_schools_spending.png" width="800">
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_per_schools_spending.png" width="800">
-  Scores by school size
      -  Same case happened to the 1000-2000 row regarding the size, we have a minor drop on the decimals and the following images could help you see the change.
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Per_schools_size.png" width="800">
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_per_schools_size.png" width="800">
-  Scores by school type
      -  and regarding the split of the school type, we see the same behavior of the district row getting reduced in their values by decimals.
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/Per_schools_type.png" width="800">
    <img src="https://github.com/SeRoGaTa/School_District_Analysis/blob/main/Images/New_per_schools_type.png" width="800">

## Summary
#### In this analysis we can see the comparison between the seven metrics for the school district after dropping all the scores from the Thomas High School 9th grade, the changes were minor as we can see in the images and statements above, but these are the four changes we can see for this school:
  - A drop of 0.1% for the overall passing rate of the district
  - No change in the ranking position of Thomas High School but with a minor change in the percentages.
  - A minor change in the split by spending, size and type in their regarding bins with an average of a .25% drop in their percentages
  - As we saw in this analysis, Thomas High School droped scores only affect in a .02% in average for their summary grades we won't see any mayor change in the metrics nor the rankings of the schools. 

#### You can locate the complete analysis code on the following link [PyCitySchools_Challenge](https://github.com/SeRoGaTa/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb) and all image used in the following folder [Images](https://github.com/SeRoGaTa/School_District_Analysis/tree/main/Images)

#### If you want to give a look to the data sets, see this folder [Resources](https://github.com/SeRoGaTa/School_District_Analysis/tree/main/Resources)

