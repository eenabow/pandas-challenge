## Pandas_challenge ##
Analyze the district-wide standardized test results and aggregate the data to and showcase obvious trends in school performance.
Final report includes each of the following:
 
* District Summary
* School Summary 
* Top Performing Schools (By % Overall Passing) 
* Bottom Performing Schools (By % Overall Passing)
* Math Scores by Grade
* Reading Scores by Grade
* Scores by School Spending
* Scores by School Size
* Scores by Type

Findings: 
  * Schools typically have a higher average reading passing % than average math passing % - Schools should focus on the math curriculum to prepare students more
  * Math Scores by grade show that the test is relatively comparable in difficulty to the year before, meaning the actual test material does not need to be reviewed.
  * School spending per student surprisingly does not equate to higher overall passing %. Opportunity to reallocate budget to provide incentives to teachers or get higher qualified teachers
  * Although small and medium sized schools produce similar overall passing students, there is a significant drop in performance in larger schools, likely due to the lack of one-on-one help from a limited number of staff
  * Charter schools have a significantly higher overall passing students percentage. This is mostly due to the application process, therefore charter schools get to selectively draw students. 



Challenges: 
  * Creating multiple boolean masks to be able to groupby different criteria
  * Finding the percentage of Passing students- this was quickly resolved by creating a new column in the original df to hold (True=1 and False=0) values instead of having to create masks each step. 
