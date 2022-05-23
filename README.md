# PyCity Schools Analysis
## Project Overview
In this project the goal is to analyze the PyCity School District data on test scores in reading and writing among all students.  Then evalutate the data to determine the following:

  - Overall district summary
  - Per school summary
  - Top 5 and bottom 5 performing schools, based on the overall passing rate
  - Average math score for each grade level from each school
  - Average reading score for each grade level from each school
  - Scores by school spending per student, by school size, and by school type

### Background
The school board determined that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. They want to uphold state-testing standards and have asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

## Results
After considering the scores of the Thomas High School ninth graders to be invalid they were replaced in the data with NaN. Below are the results of the before and after analysis and how removing the scores affected the overall district.

 ### 1. How is the district summary affected?

  #### Original Distract Summary
  <img width="1180" alt="Distict_summary_df" src="https://user-images.githubusercontent.com/102195085/169721815-148e1910-13a9-43eb-9f1f-55b8febc1e7d.png">

  #### Updated District Summary
  <img width="1180" alt="Updated_Distict_summary_df" src="https://user-images.githubusercontent.com/102195085/169721820-0abfe6a4-d59e-49d4-a9b8-e4dbdaa06714.png">

 ### 2. How is the school summary affected?
  
  #### Original School Summary
  <img width="1180" alt="Per_School_Summary_df" src="https://user-images.githubusercontent.com/102195085/169721865-969e743e-4aa8-4cb9-a302-66122c4cf349.png">

  #### Updated School Summary
  <img width="1180" alt="Updated_Per_School_Summary_df" src="https://user-images.githubusercontent.com/102195085/169721897-740bc7e7-f760-418e-8fc4-371ce826535b.png">

 ### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?


 ### 4. How does replacing the ninth-grade scores affect the math and reading scores?
    
  #### Original Math Scores
  <img width="440" alt="Math_Scores_df" src="https://user-images.githubusercontent.com/102195085/169721927-a5dac245-4922-4d19-829c-a7cbd26d169d.png">
    
  #### Updated Math Scores
  <img width="440" alt="Updated_Math_Scores_df" src="https://user-images.githubusercontent.com/102195085/169721965-a4416f3a-49ad-4eb3-a227-7571f4f3e8eb.png">

  #### Original Reading Scores
  <img width="440" alt="Reading_Scores_df" src="https://user-images.githubusercontent.com/102195085/169722022-15901bed-210d-466e-8828-751d66307a4b.png">

  #### Updated Reading Scores
  <img width="440" alt="Updated_Reading_Scores_df" src="https://user-images.githubusercontent.com/102195085/169722026-599e6b61-e712-46d1-8129-b1fdc2c9c818.png">

 ### 6. Scores by school spending:
  
  #### Original Scores by School Spending
  <img width="1180" alt="Scores_by_School_Spending_df" src="https://user-images.githubusercontent.com/102195085/169722064-9a8c7d07-58c0-4be4-958b-d053e66448d3.png">

  #### Updated Scores by School Spending
  <img width="1180" alt="Updated_Scores_by_School_Spending_df" src="https://user-images.githubusercontent.com/102195085/169722293-992e84cd-544a-470e-b04c-3499c36a26e3.png">


 ### 7. Scores by school size:
    
  #### Original Scores by School Size
  <img width="1120" alt="Scores_by_School_Size_df" src="https://user-images.githubusercontent.com/102195085/169722109-38dc4859-1165-4b04-84b4-9a3ed44052ee.png">

  #### Updated Scores by School Size
  <img width="1120" alt="Updated_Scores_by_School_Size_df" src="https://user-images.githubusercontent.com/102195085/169722125-0844bb53-6fc2-4b24-af78-1b752bce3ba8.png">

 ### 8. Scores by school type:
    
  #### Original Scores by School Type
  <img width="1050" alt="Scores_by_School_Type_df" src="https://user-images.githubusercontent.com/102195085/169722143-07e4a148-e216-4c51-b6cc-6efaf3a6da97.png">

  #### Updated Scores by School Type
  <img width="1050" alt="Updated_Scores_by_School_Type_df" src="https://user-images.githubusercontent.com/102195085/169722151-0f28ab6a-ce23-45b5-bf39-3a7f3baa1a46.png">

## Summary
