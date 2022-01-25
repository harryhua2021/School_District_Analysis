#  Overview of the school district analysis
This project aims to collect and analyze the academic performance data of Thomas High School to help investigate suspected academic dishonesty. 
The main body of the analysis focused on the performance of reading and math scores from all grade years by dissecting the data sets in several ways. 
The analysis resulted in the suspicion of academic dishonesty being placed on the 9th grade of THS. 
Based on that assumption, the school board requested that the 9th grade data be removed and the data sets were reevaluated for comparison.


#  Results
        ## How is the district summary affected?
        Original:

           The testing data of all 9th graders at Thomas High School was adjusted to NaNs (null data). After the adjustment, the analysis recalculated the percentages of students passing math, passing reading, and the overall passing. 
           The total count of students did not change because it was counted by student-ids, which was not affected by the null data.

        Adjusted: 

           With the removal of all 9th graders testing scores, the overall passing rate of math and reading in THS visibly declined, although the change is less than 1%.
           

        ## How is the school summary affected?
           Original:

           Adjusted:
           
           In the original analysis, Thomas High School enjoyed close to 91% of overall passing rate, which has sparked concerns from the school board suspecting a possiblity of academic dishonesty. After excluding all 9th grader testing scores from the calculation, the newly adjusted overall passing rate for 10 - 12th graders was significantly lower compare to the original analysis.


        ## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

            Original:

            adjusted:

            After removing the 9th grade data, THS ranking declined among the other high schools.

        ## How does replacing the ninth-grade scores affect the following:
            ### Math and reading scores by grade
            Original: 

            Adjusted: 

            The impact seems to be minimal.

            ### Scores by school spending
            Original: 

            Adjusted: 

            The impact seems to be minimal.

            ### Scores by school size
            Original: 

            Adjusted: 

            The impact seems to be minimal.
            
            ### Scores by school type
            Original: 

            Adjusted: 

            The impact seems to be minimal.


#  Summary

### The Math passing rate of THS has declined.

### The reading passing rate of THS has declined.

### The overall exam passing rate for Thomas High School declined significantly.

### The overall ranking of Thomas High School's dropped.
