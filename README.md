# School_District_Analysis
## Challenge Overview
  1. Change the scores of all 9th graders at Thomas High School to "NaN", due to their info being invalid.
  2. Determine how this affected the original analysis by answering the following questions:
        A. How is the district summary affected?
        B. How is the school summary affected?
        C. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
        D.  does replacing the ninth-grade scores affect the following: 
            I. Math and Reading Scores by Grade
            II. Scores by School Spending
            III. Scores by School Size
            IV. Scores by School type
        
## Call Out
If I were to do this analysis again, I would either take the Thomas freshman completely out or created an average for some of the analysis.  It's not accurate to show a 65% overall passing for Thomas High School, when we do not really know how the Freshman did.  It makes some of the numbers invalid.
  
## Resources
  students_complete.csv
  schools_complete.csv
 
## Challenge Summary
  1. The Disttrict Summary was negatively effected by taking out the 9th graders of Thomas High school.  The % Passing Math, % Pathing Reading and % Overall Passing all droped 1% each.  
      A. % Passing Math - old (75%) - new (74%)
      B. % Passing Reading - old (86%) - new (85%)
      C. % Overall Passing - old (65%) - new (64%)
      
  2. The analysis for Thomas high School was also affected negatively. The average math scores and reading scores stayed relatively the same, but the % passing analysis was hit hard because the freshman are still in the total, but none passed with an "NaN".
      A. % Passing Math - old (93%) - new (67%)
      B. % Passing Reading - old (97%) - new (70%)
      C. % Overall Passing - old (91%) - new (65%)
  
  3. Taking away the 9th graders' scores, Thomas High School dropped to 8th place out of all the schools in the % Overall Passing category.  With the Freshman included they sat at the number two spot. 
  
  4. The only change that happened with the scores by grade is Thomas High School's 9th grade class recieved a "NaN" instead of their average math scores of 83.6 and average reading scores of 83.7.
  
  5. Thomas High School falls into the $630 - $644 spending per student category.  After the adjustment was made this category dropped in performance:
      A. % Passing Math - old (73%) - new (67%)
      B. % Passing Reading - old (84%) - new (77%)
      C. % Overall Passing - old (63%) - new (56%) 
      
  6. Because Thomas has 1,635 students, it falls into the medium category.  Therefore, this also drove the "Medium (1000-2000)" category down. It effected it in the following ways:
      A. % Passing Math - old (94%) - new (88%)
      B. % Passing Reading - old (97%) - new (91%)
      C. % Overall Passing - old (91%) - new (85%) 
      
  7. The disctrict summary is not affected at all because Thomas High School was a charter school.  Taking the Frshman from Thomas High School drug the % Passing Math, % Passing Reading and % Overall Passing down.
      % Passing Math - old % (94), new % (90)
      % Passing Reading - old % (97), new % (93)
      % Overall Passing - old % (90), new % (87)
  
  
