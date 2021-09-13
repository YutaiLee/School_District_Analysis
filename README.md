# School_District_Analysis
## Overview of the project
### Purpose
The purpose of our analysis is to find out the overall pass rate of students and see if there is any correlation with each student’s budget. We discovered that some of Thomas High School's 9th grade test scores were missing. Therefore, we use the "NaN" value to replace the math and reading scores of the ninth grade students to adjust the previous analysis and rerun the results.
### Result
The result after replacing the math and reading scores of all ninth grade students with "NaN" (as shown below):
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/Grade_replacement_output.png)
Because Thomas’s grade 9 students’ math and reading scores have been replaced, the focus of the re-run analysis is how the adjustment affects the district’s analysis. The main focus areas are the following seven points:
* Average math and reading scores at Thomas High School
* Percentage of students passing math
* Percentage of students passing reading
* Overall percentage of students who passed math and reading score
* Percentage passing math, reading, and overall by budget per student
* Percentage passing math, reading and overall by school size
* Placement of schools overall by score values relative to each other
#### The Effects of Math and Reading Scores by Grade
After analyzing the average scores for math and reading by grade level for each school, it is found that a students grade level does not affect their scores as much as the school that they attend. However, the difference in scores is more apparent when comparing different schools.  
[The average math score](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/math_scores_grade.png)  
[The average reading score](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/reading_scores_grade.png)
#### The Effects of School Budget
We found that the average score and passing percentage do not increase with the increase in the expenditure of each student. This means that funding is not one of the important factors that determine the average grade of a student.
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/school_budget_per_student.png)
#### The Effects of School Size
We found that the average score and pass rate are the lowest in large schools. There is not much difference in performance in small and medium schools. In fact, the grades and pass rates of small and medium-sized schools have performed very well, which means that students will learn and perform better in a smaller learning environment.
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/school_size.png)
#### The Effects of School Type
We found that charter schools performed better than district schools. The top five schools with the highest overall pass rates are all charter schools, while the bottom five are all district schools. The charter schools in this dataset are usually described as small and medium size schools.
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/school_type.png)
## Summary
Reviewing the analysis of the school district metrics after replacing the Thomas High School ninth-graders' scores with the value "NaN" yielded four noteable changes to the district metrics:
1. The average math score has been reduced by 0.1%
2. The math passing percentage has been reduced by 0.2%.
3. The reading passing percentage has been reduced by 0.3%.
4. The overall passing percentage has been reduced by 0.1%.
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/THS_original_output.png)
![image](https://github.com/YutaiLee/School_District_Analysis/blob/main/Resources/THS_modified_output.png)
