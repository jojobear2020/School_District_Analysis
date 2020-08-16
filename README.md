# School_District_Analysis

## Overview of the school district analysis
The school board was notified about potential academic dishonesty, specifically, for Thomas High School (“THU” thereafter). All reading and math grades for 9th graders appear to have been altered. The purpose of this analysis is to see the impact on the original analysis results our previous results once we excluded the THU 9th graders’ scores from the overall analysis. 

## Approach
For this particular analysis we replaced all math and reading scores for THU with NaNs (missing values). It is important to note that this is not the same as making these grades equal to zero. The below link/image provides a high-level view of the impact of NaNs vs. zero on the overall average math and reading grades for all schools in total.


## Results

***Summary Level Math and Reading Scores***
Once we replaced all THU 9th graders’ math and reading scores with NaNs, we can see that it lowered the overall passing percentage. Surprisingly, it did not have a big impact on the overall average math and reading score. We can explain this by the fact that THU had only 461 9th graders, which is about 1.2% of the total students for all 15 schools. We understand, however, that keeping all THU 9th graders impacts the overall headcount and therefore skews all THU results to the lower values. To eliminate this issue, we recalculated and then replaced THU scores by using only 10th thru 12th grades data. This additional step made THU score performance metrics jump back to how we saw in our original analysis.

***Schools Level - Top and Bottom Five***

Although we did not see any drastic changes in our high-level view, we can see more impact once we look at the school level. Before the adjusted grades, THU was the second-best school by the overall passing percentage. Updating grades with NaNs shifted THU towards middle. It is no longer in top 5 schools, but it also not in bottom 5 schools either. Removing THU 9th graders put the school back to the second best spot.

***Grades Level by School***
We confirmed that using NaNs had no impact on any averages other than 9th graders average for math and reading. Overall reading score for all 9th graders from all schools, however, went down from 81.9 to 81.8. Overall math score changed from 78.9 to 78.7 (9th graders only).

***School Spending***
We also see changes in the spending per student cohort. Based on the budget and number of students, THU is categorized in $630-644 spend per student “bucket”. We see changes in this category. The overall passing for this group went down from 63% to 54%. Removing THU 9th graders data from analysis shows spending per bucket at the same level as pre-9th grade adjustment.

***Scores by school size***
In our analysis we also looked at schools by grouping them based on the number of students. Based on our categorization, THU is a mid-size school and consequently we see changes in this group metrics. If we account for 9th graders, then overall passing percentage goes down from 91% to 85%. Replacing data fir THU by using only grades 10th thru 12th puts the group numbers on about the same level as before.

***Scores by school type***
Because THU is a charter school, at first we also saw overall passing percentage drop for this group. However, replacing THU data with the 10th thru 12th graders shows very minimal impact on the overall metrics.


## Summary:

We see that all grades at THU had very high scores. If 9th graders results were indeed altered, it would not have much difference on the overall school’s performance. For the final analysis we excluded all THU 9th graders’ scores and headcount, which showed minimal impact on the overall results. If we were to keep the 9th graders scores as NaNs values, we can see from the above-mentioned analysis that it would change our outcome:

1.	THU would no longer be in top 5 performing schools
2.	Passing math percentage would be
3.	Passing reading percentage would be
4.	Overall passing percentage would be
5.	It would also impact our results for analysis by school size, spend per student, and school type.
