# pandas-challenge
Solution Challenge 4 - Pandas

## Conclusions and Comparisons From the Calculations

1. In the analysis of the shool type the charter schools have a better performance than distric shools. You can see this from the high and lowest performance school analysis the five with highest performance are charters and the five with lowest performance are district. Additionly, Scores by School Type analysis show that overall the percentage of overal passing  is arount 90% in charter schools in contrast to 50% in district schools.

2. In my analysis, I've found that medium-sized schools consistently exhibit the highest overall passing rates. This discovery sheds light on the optimal school size, which falls within the 1000 to 2000 students range. Moreover, an important observation is that schools with a lower cost per student, specifically below $585, tend to deliver the best academic performance. Investing in the infrastructure and resources of more medium-sized schools could yield substantial benefits. By maintaining an investment of less than $585 per student, the school district may allocate more funds effectively and enhance the quality of education and support services available to a larger student population. This strategic approach promises to foster improved educational outcomes and better-equipped schools for our students.


## District Summary
In the analysis of the School District, I have put together essential data points to provide a summary of 15 schools part of the district. The compilation of data contains the following key metrics: 
1.	The total number of enrolled students in the 15 schools
2.	The total budget allocation for the whole district
3.	 The average math score for the entire district
4.	 The average reading score for the entire district
5.	 The percentage of students in the entire district who passed the math assessment
6.	The percentage of students in the entire district who passed the reading assessment.
7.	The percentage of students who excelled in both math and reading.
For convenient reference, this information is organized into a data frame named "district_summary_df.” 

## School Summary 

In the analysis of the School Summary, I have put essential data points to provide a summary that allows me to see crucial points of each school in the district. This summary allows to distinguish between school type and contains the following metrics: 
1.	The total number of enrolled students in each school
2.	The total budget allocation of each school
3.	The budget allocation for each student
4.	 The average math score of each school 
5.	 The average reading score of each school
6.	 The percentage of students in each school who passed the math assessment
7.	The percentage of students in each school who passed the reading assessment
8.	The percentage of students who excelled in both math and reading in each school

For convenient reference, this information is organized into a data frame named "per_school_summary.” 

## Highest-Performing Schools by Percentage of Overall Passing
In this part of the analysis, I showed the five schools with the highest performing including the math and reading assessments. The highest percentage of passing 91.33 by Cabrera High School. 

## Lowest-Performing Schools by Percentage of Overall Passing
In this part of the analysis, I showed the five schools with the lowest performing including the math and reading assessments. The lowest percentage of passing 52.98 by Rodriguez High School. 

## Math Scores by Grade

I used the provided code to separate the data by grade. Subsequently, I grouped the data by "school_name" and computed the mean math score for each school, thus offering a comprehensive view of math proficiency at different grade levels. 

## Reading Scores by Grade
I used the provided code to separate the data by grade. Subsequently, I grouped the data by "school_name" and computed the mean reading score for each school, thus offering a comprehensive view of math proficiency at different grade levels. 

## Scores by School Spending
I used the information in per_school_summary to create a new data frame that includes the spending ranges per student together with the average of math and reading scores, percentage of passing math and reading, and overall passing. This data frame will provide a landscape of the school’s performance according to the spending ranges.

## Scores by School Size
I used the information in per_school_summary to create a new data frame that includes the school size "Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)." This information allows to know the overall and by subject passing rates regarding the school size. The medium size has the most effectiveness having the greatest overall passing rate.

## Scores by School Type
I used the information in per_school_summary to create a new data frame grouping the schools by type (charters and district). This final analysis show that the charter school model is most effective than district in terms of passing rates and scores. 
