# School_District_Analysis

## Overview
The purpose of this analysis was to provide the school district an overview of their standardized test scores and funding to help determine student performance. After initial analysis, the data was evaluated further considering the possibility that the 9th graders at Thomas High were not academically honest. 

## Results

* The District Sumarry was hardly affected with the reading and math score removal of Thomas High School 9th grade class. Actual differences can be seen in the images below, but the overall passing percentage difference was 0.3% which is not even noticed with the rounding format used here. 

The original results:
![district_sum_og](https://user-images.githubusercontent.com/104689576/186789526-a7980a90-2f1f-4afd-ab70-925aa7cc9ce0.png)

Adjusted results:
![district_sum_adj](https://user-images.githubusercontent.com/104689576/186789343-30a7bbc7-4e59-4fbb-8eae-feb7416d1aa1.png)

*	The percentage in the school summary was initally affected after recplacing the 9th grader values with null values, as the code to create the percentages calculated all values greater than 70 divided by the count of student names by school. This lowered it to 65% from the 91% it was originally, as the 9th graders were included in the total count even though they did not have scores. When the school summary used the 10-12th grade students values to replace the 9th grade students, the results were similar to before. 

*	Replacing the 9th graders values with null values caused the school to go from 2nd of 15 schools in overall passing percentage to 8th. After using the 10-12th grade scores, the school remained in the 2nd spot.

*	Replacing the the ninth-grade scores had the effects on the following comparisions:
    *	Math and reading scores by grade: Replacing the scores made little impact on the scores by grade, however it is hard to compare the new grades as the 9th graders       scores show nan. 
    *	Scores by school spending: Similarly, changing the scores did not have much impact on spending. 
    *	Scores by school size: There was little change noted in this section when the 9th grade scores were replaced. 
    *	Scores by school type: Replacing the 9th grade score also had little impact on this metric. It is noted though, that charter schools have much higher percentages       of passing students. 
    
## Summary

In conclusion, removing the 9th grade student scores had no discernible difference on the district summary analysis. It did however, cause the school to go from being 2nd in the district to 8th for overal passing percentages since there were no scores for the students. Nearly all other metrics showed little change with replacing the scores, inclduing school spending and school type. 
