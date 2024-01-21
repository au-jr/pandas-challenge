# pandas-challenge
Module 4 Challenge - Robertson, J

---
># **LGA School Data Report**
###### *John Robertson*

>## *Overview*
A recent analysis of student reading and math scores in the Local Government Area has revealed some key factors influencing the success of our students.

Our school network includes 39,170 students across 15 schools, Government and Independent run organisations, supported by a budget of $24mil. For the purpose of assessing schools and identifying areas for improvement for the future we'll look at the reading and math scores, and the pass rate for students. Looking at the current data, we're seeing only 72% of students achieving a passing score in both reading and math, suggesting there may be areas of improvement which would positively impact the outcomes for students moving forward. 

### *LGA Summary*

| Number of Schools | Student Count | Total Budget | Average Maths Score | Average Reading Score | % Passing Maths | % Passing Reading | % Passing Overall |
|---|---|---|---|---|---|---|---|
| 15 | 39170 | $24,649,428.00 | 70.34 | 69.98 | 86.08%| 84.43% | 72.81% |


As we explore the data further we find these results vary signifcantly when viewing the results in isolation based on a number of factors. Some of these factors include school type, number of students, spending per student.

>## *Results*
Comparing schools by overall passing rate, our top performer, Griffin High School (81%), saw a 15% higher rate of passing over our worst performing school, Hernandez High School (66%). Exploring these results further we can uncover the conditions leading to the success of Griffin High and identify improvements to bridge the result gap in our district.

| School Name | Type | Budget | Students | Budget per Student |	Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing | 
|---|---|---|---|---|---|---|---|---|---|
| Griffin High School | Independent | $917,500.00 | 1468 | $625.00 | 71.79 | 71.25 | 91.21% | 88.49% | 81.34% |
| Hernandez High School | Government | $3,022,020.00 | 4635 | $652.00 | 68.87 |	69.19 |	80.95% |	81.88% | 66.36% |

The five lowest performing schools have a combined 17,335 students enrolled, with a budget of $11mil. Compare this to our five best peforming school with 14,101 students and a budget of $8mil. On the surface one would expect a group of schools receiving a third less funding to see increased strain on resources leading to a reduction in students meeting passing grade. 

Further analysis has revealed that we're spending $32 more per student, $618 vs $640, at our higher performing schools. Although one would expect to find a positive correlation between budget per student and student success, the data indicates schools in the $585-630 spending bracket perform better than those in the $630-645 bracket. This suggests that there is a greater influence on the success of students than the allocated budget per student.

### *Spending Summary*

|  |	<$585 |	$585-630 |	$630-645 |	$645-680 |
|---|---|---|---|---|
| Average Math Score  |	71.36 |	72.06 |	69.86 |	68.88 |
| Average Reading Score | 70.72 | 71.03 | 69.84 | 69.05 |
| % Passing Math |	88.84% | 91.52% | 84.69% | 81.57% |
| % Passing Reading | 86.39% | 87.29% | 83.76% | 81.77% |
| % Overall Passing | 76.72% | 79.88% | 71.00% | 66.76% |


Drilling down on the information further by student population we can see that school of 1000 or fewer students saw their passing rates and combined reading and math scores perform better than schools with a greater population. Schools in the smaller student population bracket experience a student passing rate of 79%, 7% higher than the population average, and 9% higher than schools in larger population brackets. This highlights that smaller student populations are able to perform better over all.

### *Size Summary*
| | Small (<1000) | Medium (1000-2000) | Large (2000-5000) |
|---|---|---|---|
| Average Math Score | 72.34 | 71.42 | 69.75 | 
| Average Reading Score | 71.63 | 70.72 | 69.58 |
| % Passing Math | 90.81% | 89.85% | 84.25% |
| % Passing Reading | 87.56% | 86.71% | 83.30% |
| % Overall Passing | 79.07% | 78.04% | 70.29% |

Student population size may not be the only major factoring influencing the performance of our students. The school type also plays a significant role in student pass percentage. Independent schools saw an increases to reading & math scores, as well as pass rate across the board. Independent school saw overall passing rate 6% higher than Government schools.

### *School Type Summary*
|  | Government | Independent |
|---|---|---|
| Average Math Score | 69.83 | 71.37 |
|Average Reading Score |69.68 | 70.72 |
|% Passing Math | 84.46% | 89.20% |
|% Passing Reading | 83.59% | 86.25% |
|% Overall Passing | 70.70% | 76.97% |

## *Conclusion*
Taking into account all the information discovered in the analysis of reading & math scores in our distric we can can draw three distinct conclusions which could contribute to improving student scores:
1. Targetting a budget of $585-630 per student.
2. Restricting student population to 2000 or less.
3. Investigating possible expansion of Independent schools in our district.

These performance indicators should not be taken as an absolute truth, as there may be other performance indicators not identified in this data set which may impact scores to a higher degree.

---
---

# **References**

1. Takkun. (2011, May 31). How do you create different variable names while in a loop? [duplicate] (cs95, Ed.) [Review of How do you create different variable names while in a loop? [duplicate]].Https://Stackoverflow.com/. https://stackoverflow.com/questions/6181935/
how-do-you-create-different-variable-names-while-in-a-loop


2. (n.d.). pandas.DataFrame.to_excel [Review of pandas.DataFrame.to_excel]. Https://Pandas.pydata.org/; NumFOCUS. Retrieved January 19, 2024, from https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_excel.html#pandas.DataFrame.to_excel

3. Markdown Cheat Sheet | Markdown Guide. (n.d.). Www.markdownguide.org. Retrieved January 20, 2024, from https://www.markdownguide.org/cheat-sheet/#basic-syntax

‌