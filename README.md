AMCAT Analysis: Salary and Career Attributes

Overview:

The dataset was released by Aspiring Minds from the Aspiring Mind Employment Outcome 2015 (AMEO). The study is primarily limited  only to students with engineering disciplines. The dataset contains the employment outcomes of engineering graduates as dependent variables (Salary, Job Titles, and Job Locations) along with the standardized scores from three different areas – cognitive skills, technical skills and personality skills.
The dataset also contains demographic features. The dataset  contains  around  40 independent variables and 4000 data points. 
The independent variables are both continuous and categorical in nature. The dataset contains a unique identifier for each candidate. Below mentioned table contains the details for the original dataset.  

Dataset Description :

File Format: Excel (.xlsx)

Number of Rows: [ 3998 ]

Number of Columns: [ 39 ]

                      #   Column                 Non-Null Count  Dtype         
                     ---  ------                 --------------  -----         
                      0   ID                     3998 non-null   int64         
                      1   Salary                 3998 non-null   int64         
                      2   DOJ                    3998 non-null   datetime64[ns]
                      3   DOL                    3998 non-null   object        
                      4   Designation            3998 non-null   object        
                      5   JobCity                3998 non-null   object        
                      6   Gender                 3998 non-null   object        
                      7   DOB                    3998 non-null   datetime64[ns]
                      8   10percentage           3998 non-null   float64       
                      9   10board                3998 non-null   object        
                      10  12graduation           3998 non-null   int64         
                      11  12percentage           3998 non-null   float64       
                      12  12board                3998 non-null   object        
                      13  CollegeID              3998 non-null   int64         
                      14  CollegeTier            3998 non-null   int64         
                      15  Degree                 3998 non-null   object        
                      16  Specialization         3998 non-null   object        
                      17  collegeGPA             3998 non-null   float64       
                      18  CollegeCityID          3998 non-null   int64         
                      19  CollegeCityTier        3998 non-null   int64         
                      20  CollegeState           3998 non-null   object        
                      21  GraduationYear         3998 non-null   int64         
                      22  English                3998 non-null   int64         
                      23  Logical                3998 non-null   int64         
                      24  Quant                  3998 non-null   int64         
                      25  Domain                 3998 non-null   float64       
                      26  ComputerProgramming    3998 non-null   int64         
                      27  ElectronicsAndSemicon  3998 non-null   int64         
                      28  ComputerScience        3998 non-null   int64         
                      29  MechanicalEngg         3998 non-null   int64         
                      30  ElectricalEngg         3998 non-null   int64         
                      31  TelecomEngg            3998 non-null   int64         
                      32  CivilEngg              3998 non-null   int64         
                      33  conscientiousness      3998 non-null   float64       
                      34  agreeableness          3998 non-null   float64       
                      35  extraversion           3998 non-null   float64       
                      36  nueroticism            3998 non-null   float64       
                      37  openess_to_experience  3998 non-null   float64 

Columns:

Salary: The salary offered to the candidates.

Gender: Gender of the candidates (Male/Female/Other).

Specialization: Field of specialization (e.g., Computer Science, Mechanical Engineering).

Designation: Job title (e.g., Software Engineer, Analyst).

CollegeTier: Tier of the college from which the candidate graduated (e.g., Tier 1, Tier 2).

collegeGPA: Grade Point Average of the candidate.

AMCAT Personality Traits: Various traits such as conscientiousness, agreeableness, extraversion, neuroticism, and openness to experience.

GraduationYear: Year of graduation.

JobCity: City where the job is located.

10board: Educational board of the candidate's secondary education.

Exploratory Data Analysis (EDA):

Key Insights:

Salary Distribution: Analysis of the salary distribution reveals trends and potential outliers.

Gender Analysis: Insights into gender representation in different specializations and their average salaries.

Specialization vs. Salary: Examination of how different specializations affect salary levels.

Correlation with GPA: Investigated the relationship between GPA and salary, highlighting trends.

Personality Traits Correlation: Explored correlations between AMCAT personality traits and salary.

