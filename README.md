# School_District_Analysis
## Overview 
In this challenge an analysis of the data with the help of the Pandas library in Python, of an entire School District was performed, in order to obtain the funding and students grades per school and visualize the top performing schools. Additionally, to uphold state-testing standars, the analysis was performed twice due to potential academic dishonesty of the 9th graders of the Thomas High School.

## Results
Due to the potential academic dishonesty of the 9th graders of the Thomas High School, the entire 9th grade results for math and reading scores were replaced by NaNs and where ommited in the calculation of the passing percentage of the School District. The dataframe below shows a comparisson in the results of the School District averages in each assigment.

After replacing the math and reading scores of the 9th graders in Thomas High School we got these results:
* The overall passing percentage for Thomas High School fell from 90.94%  to 65.07%
* The overall passing percentage for the School District dropped from 65.17% to 64.9%
* Thomas High School was no longer part of the top 5 schools.

The percentages of passing students in Thomas High School were also affected:
* The overall passing percentages decreased 25.87%
* The passing reading percentage decreased 27.64%
* The passing math percentage decreased 26.36%

It was found that the average scores and passing percentages did not increase as spending per student increases.

## Summary
The four main changes we can see when excluding the 9th grade math and reading scores for Thomas High School are the following:

* The decrease of the overall passing percentage of the school by almost 26%.
* There is a small schange in the overall passing percentage of the school district, this value is not massively affected because of the quantity of students in the district.
