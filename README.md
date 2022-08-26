# School_District_Analysis

## Overview
The purpose of this analysis was to provide the school district an overview of their standardized test scores and funding to help determine student performance. After initial analysis, the data was evaluated further considering the possibility that the 9th graders at Thomas High were not academically honest. 

## Results

* The District Sumarry was hardly affected with the reading and math score removal of Thomas High School 9th grade class. Actual differences can be seen in the images below, but the overall passing percentage difference was 0.3% which is not even noticed with the rounding format used here. 

The original results:
![district_sum_og](https://user-images.githubusercontent.com/104689576/186789526-a7980a90-2f1f-4afd-ab70-925aa7cc9ce0.png)

Adjusted results:
![district_sum_adj](https://user-images.githubusercontent.com/104689576/186789343-30a7bbc7-4e59-4fbb-8eae-feb7416d1aa1.png)

*	The percentage in the school summary was initally affected after recplacing the 9th grader values with null values, as the code to create the percentages calculated all values greater than 70 divided by the count of student names by school. This lowered it to 65% from the 91% it was originally, as the 9th graders were included in the total count even though they did not have scores. 

*	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

*	How does replacing the ninth-grade scores affect the following:
    *	Math and reading scores by grade
    *	Scores by school spending
    *	Scores by school size
    *	Scores by school type
    
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
