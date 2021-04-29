# School_District_Analysis

## Project Overview
A City School System are working on analysis project for set of schools within their district. They requested a set tasks to be down which go as follows.
  1- Because there were signs of academic dishonesty, omit Thomas High School 9th grade from calculations.
  2- Provide an overall summary chart of all schools via per_school_summary_df. 
  3- Provide a chart that shows the top five schools via top_schools, and the bottom five schools via bottom_schools.
  4- Make two charts that show average math grades and average reading grades accross different grade levels for each school via math_scores_by_grade & reading_scores_by_grade.
  5- Include in the per_school_summary_df the effects of spending on students' overall performace. 
  6- Provide a data chart that shows the overall impact of spending for all schools on average via spending_summary_df.
  7- Include in the per_school_summary_df the effects of school size on students' overall performace.
  8- Provide a data chart that shows the overall impact of school size for all schools  via size_summary_df.
  9- A chart that compares the performace of Charter vs District schools via type_summary_df
  
## Resources
  - Data Source: schools_complete.csv, students_complete.csv
  - Software: Python 3.6.1, Jupyter

## Results


per_school_summary_df before omitting Thomas High School 9th grade class:![per_school_summary_df before edit](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/per_school_summary_df%20before%20edit.PNG)

per_school_summary_df after correction:![per_school_summary_df](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/per_school_summary_df.PNG)

The top five schools:![top_schools](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/top_schools.PNG)

The bottom five schools:![bottom_schools](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/bottom_schools.PNG)

Average math scores:![math_scores_by_grade](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/math_scores_by_grade.PNG)

Average reading scores:![reading_scores_by_grade](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/reading_scores_by_grade.PNG)

Spending summary chart divided into four groupings:![spending_summary_df](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/spending_summary_df.PNG)

Size of the student body and impact on performance chart:![size_summary_df](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/size_summary_df.PNG)

Type of school and their average performace:![type_summary_df](https://github.com/Hamza97anh/School_District_Analysis/blob/main/Images/type_summary_df.PNG)


- As far as the over all district summary is concerned. The major and most noticible effect was the replacement of Thomas High School where they were only second from the top five schools, and now they're ranked closer to the bottom. As far as over all averages, the effects were marginal since the average is taking such a large sample size so when doing an over all assesment about funding and whether charter is better than district schools that conclusion will likely be the same. 
- The school summary is most affected since Thomas High School is now ranked average as opposed to being a top rated school.
- Thomas High School prior to the omission of the 9th grade scores had an overall passing percentage of about 91%. After the correction is made, the overall passing is dropped to 63%. This is a more realistic score when compared to other scores in the district. 
  - Math and Reading scores dropped to around the 60%-70% from 90%-100%
  - Scores by school spending, school size and school type were only marginally affected since the average takes a much larger sample size. 

## Summary:

- The placement of Thomas High School dropped from being a top performer to an average school
- A drop in the percentages for spending of less then $584 per student
- Charter remains higher then District but by a smaller gap
- Small schools still out perform medium and large schools


