**Student Prefomance project** to hypothesis testing.
---
### CRISP-DM processes for data mining.
1. Business Understanding
    * Student performance can affected by enviroment. School or education place should be aware of this.

2. Data Understanding
    * Dataset 1,000 samples 8 feature with no missing value and no duplicated.
    * 5 category feature that identify specific type and background of the student.
    * 3 numberic feature that show test score in math, reading and writing.
    * Number of sample size between specific type and background of the student are not equal.
    
3. Data Preparation
    * Feature engineering by create average score of 3 test score in math, reading and writing.

4. Modeling
    * Gender's types are male and female.
        * Independent t-testing to identify a significant difference in average test score between gender's types.
    * Lunch's types are free/reduce and standard
        * Independent t-testing to identify a significant difference in average test score between lunch's types.
    * Test preparation course's types are none and completed
        * Independent t-testing to identify a significant difference in average test score between test preparation course's types.
    * Parental level of education.
        * Shapiro testing to know which groups have normal distribution for selecting next hypothesis tool.
        * Kruskal testing to identify significant differences in average test score among groups.
    * Pearson R testing to identify significant correlation between Math and Reading, Math and Writing score and Writing and Reading score.

5. Evaluate Model
    * Gender's types with independent t-testing.
        * P-value is less than 0.05, Reject the Null Hypothesis. There is a significant difference in average test score between gender types.
    * Lunch's types with independent t-testing
        * P-value is less than 0.05, Reject the Null Hypothesis. There is a significant difference in average test score between lunch types.
    * Test preparation course with independent t-testing.
        * P-value is less than 0.05, Reject the Null Hypothesis. There is a significant difference in average test score between test preparation course's types.
    * Parental level of education.
        * Shapiro testing tell these are 4 groups are normal distribution out of 5. 
        * Kruskal testing p-value is than 0.05
        Reject the Null Hypothesis. There are significant differences in average test score among the parental level of education.
    * Pearson R 
        * Math and Reading score there is significant correlation between the variables.
        * Writing and Reading score there is significant correlation between the variables.
        * Math and Writing score there is significant correlation between the variables.


6. Deployment
    * Those hypothesis testing result telling that differental in enviroment can be effect to student test performance. If school or education place or even student themself can create the good enviroment, that will be impact to test performance in good way too.