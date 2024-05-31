# pandas-challenge

# Prerequisites
Before you work on the Pandas challenge, ensure you complete the following requirements:
    - You have installed Python with the Pandas extension and Jupyter Notebook or Jupyter Lab 
    - Visual Studio Code can be used to complete this challenge
    - You are working on a Windows or MAC OS machine
    - Create a new repository named 'pandas-challenge' in GitHub for the challenge 

# Repository Setup
Complete the following steps to create a new repository:
    1. Create a new repository for this challenge called 'pandas-challenge' with a README. 
    2. Clone the new repository SSH Key to your computer.
    3. Inside your local Git repository (Git Bash), create a PyCitySchools folder.
    4. Inside the folder, copy and paste the necessary folders/files for the challenges:
        - Resources Folder with two CSV datasets
        - PyCitySchools_starter
    5. Commit and Push these changes to GitHub. 


 # About the Challenge
 The pandas challenge analyses school district performance metrics from the given datasets in two different CSV files. The following dimensions are analyzed through a series of calculations to gain insights into student performance. The dimensions include:

    1. District Summary (calculations summarize the metrics for the entire district in a data frame):
        - Total number of unique schools
        - Total number of students
        - Total budget
        - Average math and reading scores with the percentage of students who passed math and who passed reading
        - Overall percentage of students who passed BOTH math and reading tests

    2. School Summary (calculations summarize the metrics for individual schools in a data frame):
        - School name and school type
        - Total number of students in each school 
        - Total budget for each school
        - Per student budget for each school
        - Average math and reading scores with the percentage of students who passed math and who passed reading in each school
        - Overall percentage of students who passed BOTH math and reading tests in each school 

    3. Highest-Performing Schools (by % Overall Passing) (identifies the top 5 schools based on students who passed both math and reading tests):
        - Create a data frame called 'top_schools'
        - Lowest-Performing Schools (by % Overall Passing) (identifies the bottom five schools based on students who passed both math and reading tests): 
        - Create a data frame called 'bottom_schools'
    
    4. Math Scores by Grade (lists the average math score for students in different grade levels for each school):
        - Create a data frame that divides the math score per student depending on their grade level for each school (9th, 10th, 11th, 12th)
    
    5. Reading Scores by Grade  (lists the average reading score for students in different grade levels for each school):
        - Create a data frame that divides the reading score per student depending on their grade level for each school (9th, 10th, 11th & 12th)
    
    6. Scores by School Spending (this section looks into the school's performance based on average spending per student):
        - Use the bins and label information provided to create a data frame called 'spending-summary.'

    7. Scores by School Size (this section looks into the school performance based on school size and uses specific bins and labels):
        - Use the bins and labels given to filter and create a data frame called 'size_summary.'

    8. Scores by School Type (this section uses the 'per_school_summary' data frame to filter information based on school type data):
        - Use the 'per_school_summary to filter the necessary information to create a new data frame called 'type_summary.'
    
    9. Include a written report summarizing the analysis and giving insights on two different patterns or trends in the school data. 

# Instructions
 - Following the structure of the starter code to complete the cells listed above. Use appropriate methods/functions to calculate specific statistical values required in the different sections. Generate data frames for each section with corresponding variables and column names to highlight the different findings. 

# Acknowledgement 
I want to mention the following individual and resources for their assistance and support throughout this assignment:
    - UCB Tutor for guiding debugging of my script for the per_school_summary cell under the School Summary section. 
    - Ask the BCS Learning Assistant to explain the difference between specific Python functions and how to use them to calculate values appropriately.
    - Study group member(s) who helped me understand the purpose of pd.cut and how to write the code for that specific section