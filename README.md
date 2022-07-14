# School District Analysis

## Overview of the school district analysis: 
The purpose of this analysis is to take a deeper look at school performances in the district at the school and student level. Particularly with math and reading scores and passing percentages. In this analysis, we have excluded the 9th grade scores from Thomas High School as there was some question as to the corruption of these scores. These grades were shown as NaN instead of "0" so as not to corrupt the efforts of the other students at Thomas High School and the district overall.  

## Results: 

### How is the district summary affected?
The district summary is not affected to a large degree, and most of the important data points have little to no change.

### How is the school summary affected?
This is where the greatest drop in numbers is visible, but only from a percentage perspective. Thomas school was still in the top performing schools after the ninth grade scores were removed, but the overall passing percentage dropped dramatically.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The overall percentage passing rate dropped from 90% to 65% when the 9th grade scores were replaced with NaN in the analysis. While average reading and math scores were not affected to a hugely discernible degree, the passing rate percentage for math and reading individually and overall were greatly affected. Dropping from the 90's to the 60's.

### How does replacing the ninth-grade scores affect the following:
 Even with replacing the 9th grade scores, Thomas High School is still in the Top 5 Performing high schools in the district.
 
### Math and reading scores by grade
The other schools and the other grades at Thomas high school were not affected by removing the ninth grade scores and replacing them with NaN. Another benefit of using NaN instesad of "0" in the analysis is that those numbers are excluded from the averages for math and reading scores, so the other grades are not effected by the 9th grade. This helps ensure that the efforts of the 10th, 11th and 12th graders are not negatively impacted. 

The issue comes in when we calculate averages because while the NaN scores are not affecting the averages, the percentage calculation is still using the total student body count for Thomas High School, so the dip in passing percentages can be attributed to that. In future analysis, we should exclude the ninth grade student count from the Thomas High School percentage calculation to get a more accurate read.

### Scores by school spending
Not affected

### Scores by school size
Not affected

### Scores by school type
Not affected

## Summary: 
The greatest observable changes in the school district challenge before and after is the Percentage Passing Math, Percentage Passing Reading and Percentage Passing Overall for Thomas High School. This could be fixed by removing the 9th grade student count from the percentage calculation. Other than that, most of the metrics remain unchanged and decisions regarding those outcomes can be made with confidence.
