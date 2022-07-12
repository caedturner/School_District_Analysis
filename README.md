# School_District_Analysis
### Overview
###### Programs/Tools Used
(Jupyter Notebook, Conda, Python) 

  a comprehensive analysis has been done to help the school district make better informed decisions about the allocation of funds, based on performance     of schools, grade level, type of school, size of school, and the effect the budget per student each school was previously alotted.
  
  We were prompted to do a re-analysis upon discovery of evidance of academic dishonesty related to Thomas High School 9th grade class grades.

### Results
#### District Summary
  Removal of Thomas High School negatively effected the district summary in average math score, average reading score, percentage passing math, percentage passing reading and percentage passing overall.
  
###### Before Removal of Thomas High School 9th Grade Scores
<img width="1206" alt="Screen Shot 2022-07-12 at 1 14 18 PM" src="https://user-images.githubusercontent.com/106132054/178586623-67f6e672-dce1-4fd2-a0e0-546b8512c099.png">

###### After Removal of Thomas High School 9th Grade Scores
<img width="1206" alt="Screen Shot 2022-07-12 at 1 14 39 PM" src="https://user-images.githubusercontent.com/106132054/178586649-3bccf5f6-894e-4a8e-97f8-31ec022b0a84.png">

#### Most Performant Schools
  - Cabrera High School (Overall Passing % of %91.33)
  - Thomas High School (Overall Passing % of %90.63)
  - Griffin High School (Overall Passing % of %90.59)
  - Wilson High School (Overall Passing % of %90.58)
  - Pena High School (Overall Passing % of %90.54)

  All top performing schools are charter schools.
###### Most Performant Schools DataFrame
<img width="1225" alt="Screen Shot 2022-07-12 at 12 09 42 AM" src="https://user-images.githubusercontent.com/106132054/178430213-18d992c3-8f0b-4bd5-bd98-590071af6a2e.png">

#### Least Performant Schools
  - Rodriguez High School (Overall Passing % of %52.98)
  - Figueroa High School (Overall Passing % of %53.20)
  - Huang High School (Overall Passing % of %53.51)
  - Hernandez High School (Overall Passing % of %53.52)
  - Johnson High School (Overall Passing % of %53.53)

  All least performant schools are district schools.
###### Least Performant Schools DataFrame
<img width="1225" alt="Screen Shot 2022-07-12 at 12 12 45 AM" src="https://user-images.githubusercontent.com/106132054/178430661-f7cce0e3-7c7e-40c1-b400-a289093ac0a3.png">

#### Scores - Spending Ranges Per Student
  - It is facinating to see that our data shows that the schools that have the least funding per student were
    the most performant across the board (ie. average math score,	average reading score,	percentage passing math,	percentage passing reading,	             percentage overall passing)
  - The schools that have the most funding per student were also the least performant across the board.
 
 ###### Performance Based on Spending Ranges Per Student DataFrame
 <img width="1225" alt="Screen Shot 2022-07-12 at 12 40 29 AM" src="https://user-images.githubusercontent.com/106132054/178436079-888bf406-fc64-4ca9-835c-66e983a58cd7.png">
 
 #### Math Scores by Grade
 - 9th grade average: %74.78 (least performant grade)*
 - 10th grade average: %80.37
 - 11th grade average: %80.56 (most performant grade)
 - 12th grade average: %80.43
 * Thomas High School 9th grade scores were discarded due to academic dishonesty.
 
###### Math Scores by Grade DataFrame
  <img width="463" alt="Screen Shot 2022-07-12 at 12 33 50 PM" src="https://user-images.githubusercontent.com/106132054/178578956-5ce2e358-2623-4ae2-b6e9-7e8b57494b7b.png">


  #### Reading Scores by Grade
  - 9th grade average: %76.93 (least performant grade)*
  - 10th grade average: %82.50
  - 11th grade average: %82.59 (most performant grade)
  - 12th grade average: %82.56
  * Thomas High School 9th grade scores were discarded due to academic dishonesty.

###### Reading Scores by Grade DataFrame
<img width="463" alt="Screen Shot 2022-07-12 at 12 37 16 PM" src="https://user-images.githubusercontent.com/106132054/178579551-93daf63a-298b-41c7-b887-7eec294192b2.png">

#### School by Size
 When examining the school data based on the size of stdent enrollment we found:
  - Medium size (1000 - 1999) school was the most performant with an Percentage passing Overall value of %90.55. 
  - Small size (<1000) school was also very performant with an overall passing percentage of % 89.88.
  - Large size (2000 - 5000) performed very poorly with an overall passing percentage of % 58.28.

###### School by Size DataFrame
<img width="1225" alt="Screen Shot 2022-07-12 at 12 04 03 PM" src="https://user-images.githubusercontent.com/106132054/178574057-7119056e-94ff-4b3a-bb7a-9e692f20fc34.png">

#### School by Type
  When comparing Charter schools to District schools we found:
  - Charter schools have higher averages in math math and reading.
    - overall passing percentages are higher for math, reading and overall.
  - District schools tend to have lower scores in all areas.
 
###### School Type DataFrame
<img width="1225" alt="Screen Shot 2022-07-12 at 12 16 44 PM" src="https://user-images.githubusercontent.com/106132054/178576047-5140cbf3-816b-4ca4-86b2-50a28180b8b4.png">

### Summary
  The evidance of academic dishonesty has led to a slight negative effect on Thomas High School's statistics, though they remain the second most         performant school compared to all. The most notable being the negative effect found in the 9th grade performance for reading and math scores. 
##### Removal of Thomas High School Effect on Results
  - Thomas High School is a medium sized school so removal of grades for 9th graders impacted the performance of medium size schools compared to large     and small schools. 
  - Removal negatively effected the "By Grade" averages for 9th grade in reading and math scores.
  - Removal negatively effected Thomas High School's performance in math scores, reading scores as well as overall passing percentage (though                 negatively effected, Thomas High School remains the second most performant school compared to all schools).
  - very minimal negative effect on "Schools by Type."
  


