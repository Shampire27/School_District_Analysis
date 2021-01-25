# School_District_Analysis
This project was writtern with Anaconda and Jupyter Notebook under PythonData environment.  Pandas, numpy and csv file was imported for compliting this project.

## Overview of the school district analysis: Explain the purpose of this analysis.
This project was writtern for a school board who has notified by the evidence of academic dishonesty.  The evidence points to the risk that the students' reading and math grades of ninth grade students was changed in Thomas High School.  For this reason, two actions was taken to deduct the facts of data change on overall analysis:
  1. Reading and Math scores for ninth-grade Thomas High School students was adjusted
  2. School district analysis was repeated.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
The students scores lost accuracy bacause of the data missing.  The student's overall grades in Thomas High School were evaluation with bias. The standard of students' grade and teaching efficiency for Thomas High School would occur an underestimate after the score adjusted. The referance value of students' grade in district summary was reduced, while the other information (for eaxmple size and budget) remains the same.
![Thomas 9th grade scores adjusted to "NaN']((Resources/thomas_9th_NaN.png)

Total average scores and passing rate was deducted, but the difference was little which coould be ignored.
Before:
![1](Resources/1.pgn)
After:
![1_NaN](Resources/1_NaN.pgn)

- How is the school summary affected?
For Thomas High School, the results of other grades (exceot 9th grade) remains the same. However, the overall 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
  * Scores by school spending
  * Scores by school size
  * Scores by school type

## Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
