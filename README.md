# School_District_Analysis

## Purpose

The purpose of this excercise was to get familiar with the Juptyter notebook web based application, the pandas library, and further our experience with Python with data manipulation. In this particular excercise, we cleaned, summarized and formatted school district data in Jupyter Notebooks to compare and present various factors of the data against eachother.

## Results

* How is the district summary affected?

The omission of 9th grade Thomas High School scores had a minimal effect on the District Summary. The difference in % for every category stayed within 1% of change. This includes the averages for math and reading scores, as well as passing percentages. Directly below are the before and after images for reference.

Before Omission

![image_name](https://github.com/niklasax/School_District_Analysis/blob/main/Resources/District%20Summary%20(before).png)

After Omission

![image_name](https://github.com/niklasax/School_District_Analysis/blob/main/Resources/District%20Summary%20(after).png)

* How is the school summary affected?

Since Thomas Highschool was the only school with omitted scores, they were the only school affected. After omitting the ninth grade scores, the average math and reading scores stayed at approximately 83% to 84% but the biggest change was in the % who passed. Initially at Thomas High School, only around 67% passed math, 70% passed reading and 65% passed overall. After the change, Thomas High School had 93% pass Math, 97% pass reading and 90% pass overall.  

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

After replacing the ninth graders’ math and reading scores, Thomas High School’s overall performance improved relative to other schools. Initially, they had an overall passing rate of 65% which put them as the school with the 8th highest overall passing rate. After the change, their updated 90% overall passing rate put them as the school with the 2nd highest overall passing rate


* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  
  The only change would be Thomas High School in the 9th grade column showing as 'NaN' instead of the initial average
  
  * Scores by school spending
  
  The only spend category affected by the change was $630-644. With the ommision of THS 9th graders, this category would've seen increased performance for the math, reading and overall percentages.
  
  * Scores by school size
  
  The only school size category affected by the change was medium sized schools (1000-2000). With the ommision of THS 9th graders, this category would've seen increased performance for the math, reading and overall percentages.
  
  * Scores by school type
  
  The only school type category affected by the change was charter schools. With the ommision of THS 9th graders, this category would've seen increased performance for the math, reading and overall percentages.

## Summary
Four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School were omitted:

1. The overall student count dropped from 39,170 to 38,709

2. Thomas High School's performance drastically increased, bringing all passing percentages from the 60s to the 90s. This brought their overall passing rank from 8th to 2nd place.

3. 
