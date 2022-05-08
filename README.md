## School_District_Analysis

### Purpose of Analysis: 
The school board has found evidence of dishonesty with math and reading scores of 9th graders at Thomas High School. Maria has done the
analysis and reporting on Thomas High School math and reading scores. She first did a district level analysis that included the tampered data. Next she replaced math and reading scores of only Thomas High School with NaNs to see how it impacted the overall analysis.

### Results:
Q: How is the district summary affected?
A: Below are the list of changes to the school district analysis after reading and math scores were replaced.

  * Before replacing the reading and math scores with NaNs, the overall passing percentage for 15 schools was 65.17%. This reduced to         62.11% after replacing NaNs
  * The percentage of passing Reading went down from 85.80% to 85.66%
  * The percentage of passing Math went down from 74.98% to 71.93%
  * There was no change in the total budget
  
  ![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Screen%20Shot%20school%20summary.png)
  
  

### For all the 15 schools
### * How is the school summary affected?
  Below is a school summary data of all the top 5 schools. THS is at the second place with an overall passing rate of 90.63%
  ![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/top%205%20schools.png)
  
### How does replacing the ninth-grade scores affect the following:
### * Math and reading scores by grade
   After replacing with NaNs, THS's reading scores for 9th, 10th, 11th, and 12th grade reading scores were 84.3, 83.6, and 83.8.
  
  ![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Reading.png)
  
   After replacing with NaNs, THS's reading scores for 9th, 10th, 11th, and 12th grade math scores were 83.1, 83.5, and 83.5.
   
  ![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Math%20score%20by%20grade.png)
  
  As we can see, the overall impact of removing the scores of ninth graders was less than 1% across the schools. 

### * Scores by school spending

![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Score%20of%20school%20by%20pending.png)

### * Scores by school size

 ![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Scores%20by%20school%20size%20.png)
 
 Above images show that funding is not dendent on passing score and large schools have the smallest number of passing rate.
 
### * Scores by school type
![My image](https://github.com/neesha2022/School_District_Analysis_Assignment/blob/main/Resources/Screen%20Shot%202022-05-08%20at%202.33.18%20AM.png)

Charter schools are better performing than district schools. It is also evident from our top 5 and bottom 5 schools list. All the top 5 are charter schools. 
