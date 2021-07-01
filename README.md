# Module 04 Challenge - School District Analysis

|FERPA (Family Educational Rights and Privacy Act of 1974) COMPLIANCE
|:-
|Student ID Numbers, Student Names, and Student Genders are currently present within the `students_complete.csv` file provided by the School Board. This information is not disclosed and is kept private in all of the summary statistics contained within this report. However, it should be noted that this source data is currently hosted on a publicly-accessible GitHub Repository for review. While not explicitly in violation of FERPA Regulations, secure-private hosting of this sensitive data should be considered moving forward. Alternatively, the data could be sufficiently anonymized prior to public hosting.|

## Project Overview
The School Board desired an analysis of School District data to help with budgeting and planning.

The desired results were:
#### District-Wide
- Total Schools in District
- Total Students in District
- Total Budget of District
- Average Math Score of District
- Average Reading Score of District
- % of Students Passing Math in District
- % of Students Passing Reading in District
- Overall % of Students Passing both Math and Reading in District

#### Per-School
- The Type of School (Charter or District)
- A Per-School Summary of all the same category results determined previously on a District-Wide basis
- Determine and list the Top 5 and Bottom 5 Performing Schools, based on % Overall Passing
- Determine Average Math and Reading Scores by School, by Grade Level

#### Additional Analysis
- Aggregate per-Capita Spending per Student by School, arrange into 4 spending ranges such that a roughly equal number of schools falls within a given spending range. Determine for each:
	- Average Math Score
	- Average Reading Score
	- % of Students Passing Math
	- % of Students Passing Reading
	- Overall % of Students Passing both Math and Reading
- Group Schools into Small, Medium, or Large based on whether their student count is <1000, between 1000-2000, or between 2000-5000. Determine for each:
	- Average Math Score
	- Average Reading Score
	- % of Students Passing Math
	- % of Students Passing Reading
	- Overall % of Students Passing both Math and Reading
- Group Schools by Type (Charter or District). Determine for each:
	- Average Math Score
	- Average Reading Score
	- % of Students Passing Math
	- % of Students Passing Reading
	- Overall % of Students Passing both Math and Reading

We were provided with two original source data files from the School Board, as shown below in [Resources](https://github.com/TPapiernik/Module_04_Challenge#resources). These two source data files contained information for each school and student within the district. This information was combined, cross-referenced, and summarized to produce the results discussed here in this report.


|DISCLAIMER
|:-
|At the outset, it should be noted that the School Board has identified that reading and math scores may have been altered for 9th Grade Students at Thomas High School. At this time, the School Board does not know the full extend or nature of the academic dishonesty.|

Therefore, the purpose of this analysis was threefold:
1. Calculate summary statistics outlined above.
2. Exclude all Thomas High School 9th Grade Reading and Math Scores. Re-run the analysis, and determine how these changes affected the results.
3. Provide commentary and insight for Items 1. and 2. above.

## Resources
- Data Source(s): `schools_complete.csv`, `students_complete.csv` (Provided by the School Board)
- Software: Jupyter notebook server 6.3.0, running Python 3.7.10 64 bit (Dependencies: pandas, numpy)

## Results

### Data Quality
Prior to beginning the main discussion of results, it should be noted that some of the Student Name records presented in the `students_complete.csv` corpus were found to contain inaccurate name Prefixes and Suffixes such as "Dr.", "DDS", and "Miss". It is not known exactly how or when these incorrect modifications made their way into the dataset, but it can guessed that it is due to some combination of clerical error and misdirected application of youthful exhuberance.

Before starting the rest of the analysis, the Student Names in `students_complete.csv` were edited to remove the prefixes and suffixes Dr., Mr., Ms., Mrs., Miss, MD, DDS, DVM, and PhD. Other suffixes such as Jr., II, III, etc. were left in place. Overall, 1,402 student names were corrected in this manner. Should the School Board wish to receive a list of the names for upstream correction, it can be furnished upon request.

Besides the previously-mentioned qualifications, the dataset otherwise appears to be uniform, rectangular, and consistent.

### Summary of Results

See List of Figures below.

## List of Figures

### District-Wide Summary

Figure 1: District-Wide Summary (Pre-Correction)

![Figure 1](Analysis/Fig_1_Dist_Wide_original.png "Figure 1")

Figure 2: District-Wide Summary (Post-Correction)

![Figure 2](Analysis/Fig_2_Dist_Wide_corrected.png "Figure 2")


### Per-School Summary

#### Top 5 Schools

Figure 3: Top 5 Schools (Pre-Correction)

![Figure 3](Analysis/Fig_3_Top_5_original.png "Figure 3")

Figure 4: Top 5 Schools (Post-Correction)

![Figure 4](Analysis/Fig_4_Top_5_corrected.png "Figure 4")

#### Bottom 5 Schools

Figure 5: Bottom 5 Schools (Pre-Correction)

![Figure 5](Analysis/Fig_5_Bottom_5_original.png "Figure 5")

Figure 6: Bottom 5 Schools (Post-Correction)

![Figure 6](Analysis/Fig_6_Bottom_5_corrected.png "Figure 6")

#### Average Math and Reading Scores by School, by Grade Level

Figure 7: Average Math Scores by School, by Grade Level (Pre-Correction)

![Figure 7](Analysis/Fig_7_Math_by_Grade_original.png "Figure 7")

Figure 8: Average Math Scores by School, by Grade Level (Post-Correction)

![Figure 8](Analysis/Fig_8_Math_by_Grade_corrected.png "Figure 8")

Figure 9: Average Reading Scores by School, by Grade Level (Pre-Correction)

![Figure 9](Analysis/Fig_9_Reading_by_Grade_original.png "Figure 9")

Figure 10: Average Reading Scores by School, by Grade Level (Post-Correction)

![Figure 10](Analysis/Fig_10_Reading_by_Grade_corrected.png "Figure 10")

### Additional Analysis

#### Per-Capita Spending by School



#### School Size



#### School Type
