# School District Analysis
## Overview
After discovering evidence of academic dishonesty, the analysis made with PyCitySchools.ipynb needed to be corrected. By taking out data from Thomas High School's freshman class, how does the overall district analysis change?\

## Results
The district analysis was extensive, and changing the data will have a wide-ranging ripple effect. Listed below are the different analyses and how they changed:
### - District Summary
- The original analysis:
 
![Original District Summary](/Resources/district_summary_mod.PNG)
- The adjusted analysis:

![Adjusted District Summary](/Resources/district_summary_chal.PNG)

All the passing percentages were changed, though they were all changed marginally, not changing more than a few tenths of a percent at most.
### - School Summary
- The original analysis:

![Original School Summary](/Resources/per_school_summary_mod.PNG)
- The adjusted analysis:

![Adjusted School_Summary](/Resources/per_school_summary_chal.PNG)

A lot of text and numbers, but the only changes are in Thomas High School's row. Again, the changes were marginal, not being more than 3 tenths in any column.
### - Thomas High School's Relative Performance
Before the adjustment, Thomas High School had the second highest Overall Passing Percentage:

![Original Top Schools](/Resources/top_schools_mod.PNG)

Here are the top 5 schools based on Overall Passing Percentage after the adjustment:

![Adjusted Top Schools](/Resources/top_schools_chal.PNG)

As you can see, Thomas High School remains the second best performer. The change of .3% in its overall performance wasn't significant.
### - Other Analyses
This analysis also covered math and reading scores by grade, scores by school spending, scores by school size, and scores by school type.
#### Scores by Grade
- Original Analysis:

![Math Scores by Grade](/Resources/math_scores_grade_mod.PNG) ![Reading Scores by Grade](/Resources/reading_scores_grade_mod.PNG)
- Adjusted Analysis

![Math Scores by Grade](/Resources/math_scores_grade_chal.PNG) ![Reading Scores by Grade](/Resources/reading_scores_grade_chal.PNG)

This is a perfect example of how the other sets of data weren't changed by the adjustment. All the numbers are exactly the same, save for a "nan" in the 9th grade column in the Thomas High School row.
#### Scores by Spending
- Original Analysis

![Spending Summary](/Resources/spending_summary_mod.PNG)
- Adjusted Analysis

![Spending Summary](/Resources/spending_summary_chal.PNG)

Thomas High School was in the third "bin" ($631-645), but the removal of the 9th grade scores did not change this analysis.
#### Scores by Size
- Original Analysis

![Size Summary](/Resources/school_size_mod.PNG)
- Adjusted Analysis

![Size Summary](/Resources/school_size_chal.PNG)

Thomas High School, with 1635 students, would fit into the Medium category. As like the previous, no change to this analysis.
#### Scores by Type
- Original Analysis

![Type Summary](/Resources/type_summary_mod.PNG)
- Adjusted Analysis

![Type Summary](/Resources/type_summary_chal.PNG)

Thomas High School is a charter school. As with the last two, no change in the analysis. This would make sense, as each of the last three analyses were grouping larger groups, and the larger the group, or "bin," the less the adjustment would affect the data.
## Summary
Overall, the change in scores was minimal, highlighting the effectiveness of having a large data set. The changes in the overall analysis were in four places. Those were:
- District Summary
- School Summary
- Relative Perfomance
- Scores by Grade

The Scores by Grade wasn't changed aside from the removal of Thomas High School's Freshman data, resulting in a "nan" output in their respective data frames. Aside from the Scores by Grade, the changes in the results were less than a few tenths at most, not enough to draw any new conclusions from the original analysis. 
