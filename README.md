# Module 04 Challenge - School District Analysis

## Project Overview
The School Board desired an analysis of School District data to help with budgeting and planning.

The results desired were:
#### District-Wide
- Total Schools in District
- Total Students in District
- Total Budget of District
- Average Math Score of District
- Average Reading Score of District
- % of Students Passing Math
- % of Students Passing Reading
- Overall % of Students Passing both Math and Reading

#### Per-School
- The Type of School (Charter or District)
- A Per-School Summary of all the same category results determined previously on a District-Wide basis
- Determine and list the Top 5 and Bottom 5 Performing Schools, based on % Overall Passing
- Determine Average Math and Reading Scores by School, by Grade Level

#### Additional Analysis
- Aggregate per-Capita Spending per Student by School, arrange into 4 spending ranges such that a roughly equal number of schools falls within a given spending range, and determine for each the Average Math Score, Average Reading Score, % of Students Passing Math, % of Students Passing Reading, and Overall % of Students Passing both Math and Reading
- Group Schools into Small, Medium, or Large based on whether their student count is <1000, between 1000-2000, or between 2000-5000. Determine for each the Average Math Score, Average Reading Score, % of Students Passing Math, % of Students Passing Reading, and Overall % of Students Passing both Math and Reading
- Group Schools by Type (Charter or District). Determine for each the Average Math Score, Average Reading Score, % of Students Passing Math, % of Students Passing Reading, and Overall % of Students Passing both Math and Reading

We were provided with two original source data files from the School Board, as shown below in [Resources](https://github.com/TPapiernik/Module_04_Challenge#resources). These two source data files contained information for each school and student within the district. This information was combined, cross-referenced, and summarized to produce the results discussed here in this report.

### FERPA (Family Educational Rights and Privacy Act of 1974) COMPLIANCE
|Student ID Numbers, Student Names, and Student Genders are currently present within the `students_complete.csv` file provided by the School Board. This information is not disclosed and is kept private in all of the summary statistics contained within this report. However, it should be noted that this source data is currently hosted on a publicly accessible GitHub Repository for review. While not explicitly in violation of FERPA Regulations, for heightened security and privacy of this sensitive data, secure-private hosting should be considered moving forward. Alternatively, the data should be sufficiently anonymized prior to public hosting.|
|-

### DISCLAIMER
|At the outset, it should be noted that the School Board has identified that reading and math scores may have been altered for 9th Grade Students at Thomas High School. At this time, the School Board does not know the full extend or nature of the academic dishonesty.|
|-

Therefore, the purpose of this analysis was threefold:
1. Calculate summary statistics for the entire school district, reporting them in a variety of formats.
2. Exclude all Thomas High School 9th Grade Reading and Math Scores, re-run the analysis, and determine how these changes affected the overall district-level results.
3. Provide commentary and insight for Items 1. and 2. above.

## Resources
- Data Source(s): `schools_complete.csv`, `students_complete.csv` (Provided by the School Board)
- Software: Jupyter notebook server 6.3.0, running Python 3.7.10 64 bit (Dependencies: pandas, numpy)

## Results
