# School_District_Analysis

## Background and Purpose

Upon the suspicion of academic dishonesty, the school board has requested that math and reading scores for ninth grade Thomas High School be removed from our current analysis.  I have re-calculated the analysis per this request. These new figures may be used to generate an updated school district analysis in order to drive budgeting and set priorities for the schools within the district, until the Thomas High School issue is resolved.

## Results

### District Summary

When assessing average scores and passing percentages among the 15 high schools in the school district, no significant changes were noted. The average math score dropped .1 point, the average reading score stayed the same, the percentage passing math, the percentage passing reading, and the overall passing percentage all dropped 1%. 

![image](https://user-images.githubusercontent.com/95661802/150656418-aac42187-26ce-404e-a596-484c2b5edb44.png)


### School Summary

The re-calculation impacted the school summary statistics significantly. Thomas High Shcool how displayed 66.9% math passing percentage (previously 93.3%), 69.6% reading passing percentage (previously 97.3%), and an overall passing percent rate of 65.1% (previously 90.1%). This resulted in Thomas High School no longer being one of top 5 performing schools. 

![image](https://user-images.githubusercontent.com/95661802/150656473-d69982a2-2c78-472f-97f3-4d88e5b4cf3d.png)

The re-calculation impacted the school summary statistics significantly. Thomas High Shcool how displayed 66.9% math passing percentage (previously 93.3%), 69.6% reading passing percentage (previously 97.3%), and an overall passing percent rate of 65.1% (previously 90.1%). This resulted in Thomas High School no longer being one of top 5 performing schools. 

#### Top Performing Schools

![image](https://user-images.githubusercontent.com/95661802/150656496-fe2ce8c2-03d4-4b1d-acbd-48b7691e077d.png)

#### Bottom Performing Schools

Good news -- it was not in the bottom 5 performing schools either.

![image](https://user-images.githubusercontent.com/95661802/150656507-4c1bc04c-432b-4220-be02-086f8117049b.png)


### Average Math & Reading scores

The average math and reading scores remained unchanged, except for ninth graders in Thomas High School (as these were set to NaN values).

#### Average Math Scores by Grade Level for Each School

![image](https://user-images.githubusercontent.com/95661802/150656550-473636be-8aa4-476a-9c09-848dd81c8357.png)

#### Average Reading Scores by Grade Level for Each School

![image](https://user-images.githubusercontent.com/95661802/150656561-bb867169-acda-4a39-8851-e9814a97ab45.png)

### School Spending Summary

When reviewing the school spending summary data, there was a 6% decrease in passing math percentage, a 7% decrease in passing reading percentage, and a 7% decrease in overall passing percentage in the $630-$644 spending range per student.

![image](https://user-images.githubusercontent.com/95661802/150656583-1d7f0660-ef20-48e7-a9a8-4295f391bf93.png)

### Scores by Schools Size Summary

When reviewing the data for scores according to school size, there was a 6% decrease noted for passing math percentage, passing reading percentage, and overall passing percentage. According to the original data, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small-sized (90% overall passing) and large schools (58% overall passing). Given the data change, medium-sized schools are now the second in performance by size (85% overall passing).

![image](https://user-images.githubusercontent.com/95661802/150656605-68e17ceb-9170-420e-a836-17e975744f9a.png)

### Scores by School Type

The re-calculation negatively impacted the charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now had a 90% passing math, 93% passing reading, 87% overall passing. However, even with these changes, charter schools outperform district schools.

![image](https://user-images.githubusercontent.com/95661802/150656614-962bb263-3cc5-4778-8e3b-ebd7f1823cee.png)

## Summary

In summary, after the reading and math scores for ninth grade at Thomas High School were replaced with NaN values, there were four notable changes in the data. First, overall student count for the district that had a passing math and reading score was reduced, which impacted the passing math, passing reading and overal passing percentages forth district (albiet not my much). Secondly, scores within the $630-$644 spending ranges were lower, that can have an impact on school budgeting decisions. Thirdly, scores based on school size also decreased. This would be more in line with what one would expect, smaller student-to-teacher ratios woul yield better grades. Finally, scores by school type also changed. Scores for charter schools dropped by about 3%-4%, however, this was not significant enough to close the gap between how the two different school types performed overall. Students at district schools still remain far behind their peers at charter schools.
