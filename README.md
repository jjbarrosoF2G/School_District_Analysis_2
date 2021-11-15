# School District Analysis

## Overview
### This project is to analyze the data of Math & Reading scores from an entire School District. In order to find new insights on each school's performance, and to provide guidance in budget allocation.

## Results
The analysis was done twice because due to suspicion of dishonesty by some 9th grade students from the Thomas High School.
Round #1 - Included the full data set.
Round #2 - Data for 9th grade students in Thomas High School was replaced with NaN.

The main changes in results from this substitution were:

**Overall Passing grade**
- Replacing 9th graders' math & reading scores with NaN resulted in:
- The original summary results for the district were:
![original district summary](https://github.com/jjbarrosoF2G/School_District_Analysis_2/blob/main/Resources/02%20District%20Summary%20original.png)

- The revised summary results for the district are:
![revised district summary](https://github.com/jjbarrosoF2G/School_District_Analysis_2/blob/main/Resources/01%20District%20summary%20df.png)

**Overall Passing grade**
- Replacing 9th graders' math & reading scores with NaN resulted in:
  - Thomas High School no longer being in the Top five schools.
  - The overall passing percentage for the entire district fell to 64.9%
  - Overall passing percentage for Thomas High School fell to 65%
  
- When 9th graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:
  - The overall passing percentages of Thomas High School decreased by 0.11%
  - The average scores of Thomas High School for math and reading *increased* by 0.06
  - For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%



## Summary
Unfortunately, it is not possible to determine the extent of the potential academic dishonesty or identify soecific indivuals to exclude from the dataset. As a consequence of this, the entire ninth grade of students from Thomas High School have had their scores omitted from the results. This is a suboptimal situation because a full set of data is ideal for creating the most accurate results.

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. To view the full script, please open PyCitySchools_Challenge.ipynb in Jupyter Notebook.

## Resources
**Software:** Python, Anaconda, and Jupyter Notebook
**Data:** Data used in this analysis can be found in the Resources folder (https://github.com/jjbarrosoF2G/School_District_Analysis_2/tree/main/Resources).

