# PyCity Schools

## Project Overview

This project uses Python Pandas to analyze [the data](PyCitySchool/Resources) from district-wide standarized test results to showcase trends in school performance. 

## Technologies Used

- Python
- Pandas
- Jupyter Notebook

## Data Analysis

First [the analysis](PyCitySchools/PyCitySchools_complete.ipynb) is done at the district level and summarizes: 
- Total Schools
- Total Students
- Total Budget
- Average Math Score
- Average Reading Score
- % Passing Math
- % Passing Reading
- Overall Passing Rate (Average of the above two) 

Then the same analysis is done at the school level, and the 5 lowest performing schools are highligthed.

Math and Reading test scores are then analyzed by grade (9th, 10th, 11th, 12th) at each school. Finally, the test scores are analyzed as a function of spending, school size, and type of school.

## Conclusion

Some trends that can be seen from this analysis:

1. The schools that spend the most amount of money per student are the lowest scoring schools.

2. Observing the trend in Overall Passing Rate with respect to School Size, the highest scoring schools have a population that falls primarily within the medium-large range.

3. There is a very direct relationship between high test scores and School TYPE. That is, every Charter school scored higher than every District school. The reason behind this may not be as clearcut at the data, however. Charter schools have more flexibility in offering innovative educational approaches, perhaps this is helpful for adapting lessons to a range of students and a variety of learning styles. However, it is also important to note that Charter schools are BY CHOICE, whereas public schools are by default. Parents choose to send their kids to Charter school and often this involves a lottery and being held on a waiting list for a while before obtaining a spot for your child. Therefore, the students that end up at Charter schools already fall into a certain demographic: their parents actively pursue the best educational opportunities for their child. It is likely that these are students who value an education, behavior modeled by their parents, and have educational support at home. This could be a large factor contributing to the stark distinction between Charter and District schools with regard to Overall Passing Rate.
