# School_District_Analysis

## 1. Overview of the school district analysis
Purpose of Analysis

Maria has asked for help to compute some analysis on the school district that she works in. After compiling all of the relative data relating the both the schools as well as the students, Maria wanted me to look at how replacing the 9th graders scores at Thomas High School would effect the different analyses that we have to perform. I used pandas to use the original analysis as well as to create a new one.  


## 2. Results

Questions

We are going to look at the following comparisons between two analyses.

- How is the district summary affected?
  Based on the results we see that there is a small change of .1% drop in average math scores between the two analyses
![district_summary1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/district_summary1.png)
![district_summary2](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/district_summary2.png)

- How is the school summary affected?

  When we look at the statistics we can see that Thomas High Schools statistic for both math and reading scores dropped.
![school_summary1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_summary1.png)
![school_summary2](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_summary2.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  Thomas High School scores have been significantly affected by dropping quite a lot. 

- How does replacing the ninth-grade scores affect the following:

  Math and reading scores by grade
    - When we run the scores we see that the 9th graders at Thomas High School averages are higher than the other schools. 
![ninth-grade_scores1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/ninth-grade_scores1.png)
![ninth-grade_scores2](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/ninth-grade_scores2.png)

  Scores by school spending
    - Based on the percentages and the ranges the $630 to $644 range dropped from 63% to 56% overall passing percentage
![spending_ranges1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/spending_ranges1.png)
![spending_ranges2](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/spending_ranges2.png)

   Scores by school size
      - Based on the school size scores the 1000 to 2000 size schools dropped from 91% to 85% overall passing percentage.
![school_size1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_size1.png)
![school_size2.png](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_size2.png)

  Scores by school type
    - Based on the school type results there was a drop from 90% to 87% overall passing percentage
![school_type1](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_type1.png)
![school_type2](https://github.com/cbrito3/School_District_Analysis/blob/main/pictures/school_type1.png)

## 3. Summary 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
The four changes in the updated reading and math scores for the ninth grade at Thomas High School have been replaced with NaNS are the following:
 1. If we do not include the scores of the ninth grade, Thomas High School is not as competitive with other schools.
 2. If we do not include Thomas High School in the list of schools there is an overall ninth grade scores drop.
 3. The district summary changes less if we do not include the ninth grade scores.
 4. Although there is not significant changes in the ninth grade scores it balances with the other scores. 
