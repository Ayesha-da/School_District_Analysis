# School_District_Analysis
## Overview
To Analyze data on student funding and student standardize test scores.To aggregate data and showcase trends in school performance which will assist in making decisions regarding school budgets and priorities.
### Purpose
Reading and math grades for Thomas High School ninth graders appear to have been altered.Task is to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact and repeat the school district analysis and describe how these changes affected the overall analysis.
## Results
#### •How is the district summary affected?

There is slight difference at district level after dropping the 9th grade scores of Thomas High school.

![district_summary1](https://user-images.githubusercontent.com/84524153/124364236-2696c500-dc0e-11eb-8300-e473dea18887.png)
![district_summary2](https://user-images.githubusercontent.com/84524153/124362424-afa7ff00-dc02-11eb-95f0-b148f3f67853.png)


#### •How is the school summary affected?
In the school summary, only Thomas High school metrics has changed and the rest of the data remains intact. The school's passing percentage for math, reading and overall, has improved significantly.

![thomas_hs1](https://user-images.githubusercontent.com/84524153/124355131-a7899880-dbdd-11eb-8333-82fdf8b97ebf.png)
![thomas_hs2](https://user-images.githubusercontent.com/84524153/124355144-b5d7b480-dbdd-11eb-9477-7d0ab7dc757c.png)

#### •How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 Thomas High school was among low performing schools(bottom schools). After ninth grade scores are removed , it became second best among top performing schools.
![bottom-schools](https://user-images.githubusercontent.com/84524153/124362835-80df5800-dc05-11eb-92f0-57bc4cf54acd.png)

![top_schools](https://user-images.githubusercontent.com/84524153/124362841-876dcf80-dc05-11eb-891f-d16d0a53351b.png)

#### •How does replacing the ninth-grade scores affect the following:

##### •Math and reading scores by grade

 Ninth grade math and reading scores of Thomas High School are changed to NaN and the rest of the grade scores for all the schools remain intact.
 
![math_score](https://user-images.githubusercontent.com/84524153/124357812-7021e880-dbeb-11eb-8c02-f1da3afa16f4.png)
![reading_score](https://user-images.githubusercontent.com/84524153/124357817-7912ba00-dbeb-11eb-942d-a114477b094d.png)

##### •Scores by school spending

Thomas High school's budget per student is $ 638.00 and the school is in  $630-644 of school spending range. The performance metrics of %passing math, %passing reading and overall passing has improved in this range due to change in Thomas high school data.

![school_spending1](https://user-images.githubusercontent.com/84524153/124357529-ff2e0100-dbe9-11eb-8915-1297a8b9ff41.png)
![school_spending2](https://user-images.githubusercontent.com/84524153/124357536-06eda580-dbea-11eb-893c-78bc078bf5c0.png)

##### •Scores by school size

Thomas High school falls in medium size school category and so passing math, passing reading and overall passing percentages of medium size schools has improved.

![school_size1](https://user-images.githubusercontent.com/84524153/124357544-110fa400-dbea-11eb-8f0c-4866b7ea5d8a.png)
![school_size2](https://user-images.githubusercontent.com/84524153/124357554-1a990c00-dbea-11eb-9494-7c47ef6079f4.png)

##### •Scores by school type

Thomas High School is a 'charter school' and dropping it's ninth grade scores has increased the performance of charter schools in math, reading and overall passing percentage.

![school_type1](https://user-images.githubusercontent.com/84524153/124357569-343a5380-dbea-11eb-9546-74235a155be5.png)
![school_type2](https://user-images.githubusercontent.com/84524153/124357572-38ff0780-dbea-11eb-9ab4-6b478e127624.png)

## Summary
 Four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:
 - Thomas High school's passing percentage in math, reading and overall, became better and school is ranked second best among all schools.
 - Performance metrics of school spending range of $ 630-644 has improved.
 - Medium size school overall performance and performance in math and reading has improved.
 - Charter schools overall performance and performance in math and reading  has improved.
