# School District Analysis

## Overview
We were tasked by Maria, an employee of a school district, to gather and analyze data on High Schools and their students in the school district. We had initially displayed and formatted data frames regarding the Reading and Math scores for each student. However, we were informed that there was evidence of academic dishonesty among Reading and Math grades for Thomas High School 9th graders. We were asked to remove the Math and Reading scores for all Thomas High School 9th graders.

## Results

*How is the district summary affected?*
The district summary from before the changes we made showed slightly higher passing percentages for both reading and math. Below is the data from the original analysis:
![district_summary.png](/Resources/district_summary.png)

Compared to the new analysis with the replacement of THS ninth grader data:
![district_summary_challenge](/Resources/district_summary.png)

Comparing the two data frames, we can also see the decrease in the the total number of students since we had removed the ninth-graders from THS.

*How is the school summary affected?*

In the original data frame for the school summary, Thomas High School had a slightly higher overall passing percentage for all students with 90.95%:
![THS_school_summary.png](/Resources/THS_summary.png)

After replacing the ninth grade date however, the overall passing percentage for all students became 90.63%:
![THS__school_summary_Challenge.png](/Resources/THS_summary_Challenge.png)

*How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?*

Although Thomas High School remains as the second best school with overall passing percentage, the overall percentage did decrease by about .3%.

*How does replacing the ninth-grade scores affect the following:*

--*Math and reading scores by grade*

The difference between these data frames is apparent in the 9th grade column for Thomas High School. The original analysis included the Thomas High School ninth graders, while in the new analysis we had replaced the 9th grader data with NaN.

The original math scores by grade:
![math_scores_by_grade.png](/Resources/math_scores_by_grade.png)

The new math scores by grade:
![math_scores_by_grade_challenge.png](/Resources/math_scores_by_grade_challenge.png)

The original reading scores by grade:
![reading_scores_by_grade.png](/Resources/reading_scores_by_grade.png)

The new reading scores by grade:
![reading_scores_by_grade_challenge.png](/Resources/reading_scores_by_grade_challenge.png

--*Scores by school spending*

The difference between the scores by spending is that the $630-644 spending per student bin had decreased across the board for the average scores and percentages.

From before the changes:
![spending_summary.png](/Resources/spending_summary.png)

After the changes:
![spending_summary_challenge.png](/Resources/spending_summary_challenge.png)

--*Scores by school size
Due to Thomas High School being a "Medium" sized school with 1000-1999 students, the only row that showed changes was the Medium School Size. The overall passing percentage declined due to our changes as seen below.

Original data:
![size_summary.png](/Resources/size_summary.png)

After the replacement of Thomas High School ninth graders:
![size_summary_challenge.png](/Resources/size_summary_challenge.png)

--*Scores by school type*
Luckily, we did not see much of a change in the school summary when separated by type of school, district or charter.

Original data:
![type_summary.png](/Resources/type_summary.png)

After the replacement of Thomas High School ninth graders:
![type_summary_challenge.png](/Resources/type_summary_challenge.png)

## Summary

The changes we applied by omitting Thomas High School 9th grade scores changed the analysis in four different ways:

	i. Comparing scores by grade, it is apparent that 9th grade scores for Thomas High School is replaced with NaN.
	ii. The overall passing percent declined for Medium sized schools.
	iii. The difference between the scores by spending is that the $630-644 spending per student bin had decreased across the board for the average scores and percentages.
	iv. The total number of students decreased by several hundred.