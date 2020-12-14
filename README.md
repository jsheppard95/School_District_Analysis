# School_District_Analysis

## Overview of the school district analysis
This repository contains Jupyter Notebook files to read and analyze school district data [schools_complete.csv](Resources/schools_complete.csv)
and [students_complete.csv](Resources/students_complete.csv). The schools data file has format `School ID,school_name,type,size,budget` and the
students data file has format `Student ID,student_name,gender,grade,school_name,reading_score,math_score`. We use this information to analyze
the district as a whole, determining the top and bottom five performing schools by overall passing rate (having a math and reading score greater
than 70), the average math and reading score by grade level for each school, along with the average scores and percentage passing by school
spending, school size, and school type. Finally, we duplicate this analysis with the ninth grade math and reading scores of Thomas High School
removed to determine if this has a significant effect on the performance of both this school relative to the entire distribution and the
district as a whole.

## Results
- District Summary
  - [Removing Thomas High School Ninth Grade Scores](Resources/district_summary_thomas_removed.png)
    - Average Math Score: 78.9
    - Average Reading Score: 81.9
    - % Passing Math: 74.8
    - % Passing Reading: 85.7
    - % Overall Passing: 64.9
  - [All School Data](Resources/district_summary_all.png)
    - Average Math Score: 79.0
    - Average Reading Score: 81.9
    - % Passing Math: 75.0
    - % Passing Reading: 85.8
    - % Overall Passing: 65.2
- School Summary
