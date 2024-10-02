# Student Demographics Analysis Using Tableau

## Overview

This project explores the demographics of students that applied to **Tech Moms** program using application data. The dataset provides insights into the employment status, education levels, household income, and diversity of the applicants. Using Tableau, I visualized key trends such as employment categories, income distribution, and the representation of various racial and ethnic groups. The goal is to understand the applicant / student profile and support program decision-making for future cohorts.

## Project Details

### 1. Dataset

The dataset consists of various fields including:
- **Applicant Status**: Tracks the application status (e.g., "Assigned Cohort", "Declined Attending").
- **Employment Status**: Includes categories such as "Full-Time", "Part-Time", and "Unemployed."
- **Education Level**: Ranges from "Some College" to "Bachelor's or Above."
- **Household Income**: Shows the income brackets for each applicant's household.
- **Race/Ethnicity**: Identifies the racial or ethnic group of the applicants.
- **Create Date**: The date when the application was submitted.

### 2. Data Preparation in Tableau

- **Imported the CSV file** into Tableau.
- Created calculated fields to categorize **employment status** (e.g., "Unemployed", "Full-Time", "Part-Time").
- Used **Level of Detail (LOD)** expressions to calculate percentages for specific groups, such as unemployed applicants and different income levels.
- Segmented the applicants by **education level** and **race/ethnicity** for more granular analysis.

### 3. Key Visualizations

#### Employment Status Breakdown (Sheet 1)
- **Visualized the employment distribution** of the students.
- **Purpose**: Identify how many students are unemployed, part-time, or full-time to assess the need for career support.
- **Visualization Type**: Pie chart, labeled "Employment Status"

#### Income Distribution (Sheet 2)
- **Visualized the household income** distribution of students.
- **Purpose**: Assess the financial backgrounds of students and identify income brackets.
- **Visualization Type**: Bar chart, labeled "Household Income."

#### Marital Status Distribution (Sheet 3)
- **Visualized the marital status** distribution of students, showing whether they are single, married, or in other relationship statuses.
- **Purpose**: Understand the marital status distribution of applicants, which can provide insight into potential responsibilities (such as family obligations) that may impact their availability or participation in the program.
- **Visualization Type**: Bar chart, labeled "Marital Status"

#### Number of Children Distribution (Sheet 4)

- **Visualized the distribution of the number of children that each student has**, ranging from null, 0, 1, up to 9 children.
- **Purpose**: To understand the family responsibilities of the applicants. This can help the program identify potential challenges students may face in balancing their coursework with childcare, and assist in tailoring support services for parents, particularly those with larger families or those without children.
- **Visualization Type**: Bar chart, labeled "Number of Children Distribution"

#### Education Level Breakdown (Sheet 5)
- **Explored the education levels** of the applicants.
- **Purpose**: Understand the educational qualifications of the applicant pool, from high school to bachelor's degree.
- **Visualization Type**: Bar chart, labeled "Education Level Breakdown."

#### Diversity Representation (Sheet 6)
- **Displayed the racial and ethnic composition** of the applicants, focusing on BIPOC+ groups.
- **Purpose**: Analyze the diversity of the program's applicants.
- **Visualization Type**: Pie chart, labeled "Diversity Representation."

#### Number of Students per Cohort (Sheet 7)
- **Visualized the number of students per cohort from 2020 to 2024**, showing a growth trend from 14 students in 2020 to 27 in the most recent cohort, with a notable dip to 14 students in the previous-to-last cohort.
- **Purpose**: To analyze the growth and fluctuations in cohort sizes over time, providing insight into the program's expansion and potential factors contributing to the dip in enrollment in the second-to-last cohort. Understanding cohort sizes can help program organizers assess capacity, resource needs, and recruitment strategies.
**Visualization Type**: Line chart or bar chart, labeled "Number of Students per Cohort"

#### Key Performance Indicators (Sheet 8)
This section highlights the most important demographic metrics of the applicants:
- **Unemployed (30.40%)**: A significant portion (30.40%) of the applicants are unemployed, indicating that the program is reaching individuals who are likely seeking career development and job opportunities.
- **Household Income <50K (43.88%)**: Almost half (43.88%) of the applicants come from households with an annual income of less than $50,000, highlighting the potential financial challenges faced by many applicants.
- **Single Mothers (42.09%)**: A substantial 42.09% of the applicants are single mothers, suggesting that a significant portion of the program participants may need additional support balancing parenting responsibilities with their participation in the program.
- **High School / Some College (51.98%)**: Over half (51.98%) of the applicants have only a high school diploma or some college education, showing that many participants may be seeking further education or upskilling opportunities.
- **BIPOC+ (37.23%)**: 37.23% of the applicants identify as Black, Indigenous, People of Color (BIPOC+), indicating that the program is serving a diverse population, though there remains room for outreach to other underrepresented groups.

### 4. Final Dashboard
- Combined all visualizations into a comprehensive dashboard named **Student Demographics**.
- **Purpose**: Provide a full overview of the employment, income, education, and diversity trends for students applying to the Tech Moms program.

<a href="https://public.tableau.com/views/Student_Demographics_17278393621850/StudentDemographics?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link">
  <img src="https://github.com/user-attachments/assets/d4c1cfcf-5f80-4017-9366-af929abbc21c">
</a>

## Tools Used
- **Tableau Public**: Used for data preparation, analysis, and visualization.
- **CSV**: Cleaned dataset containing application details for the Tech Moms program.

## How to Use
1. **Open Tableau Workbook**: Access the workbook via Tableau Public to explore the visualizations and interact with the dashboard.
2. **Explore Visualizations**: Use filters to adjust the data and focus on specific employment categories, education levels, or income ranges.
3. **Understand the Insights**: Use the dashboard to identify key trends in student demographics and inform program planning and outreach.

## Key Insights

- **Employment Trends**:  
  30% of students are unemployed, which suggests a need for career development opportunities in the Tech Moms program. A majority are employed full-time or part-time, showing a balance between work and upskilling.

- **Income Distribution**:  
  A significant portion of applicants fall into lower-income brackets, highlighting the potential need for financial support options for participants.

- **Education Levels**:  
  A large proportion of the students hold high school or some college education, with 40% holding a bachelor’s degree or higher, indicating a mix of applicants seeking to further their education.

- **Diversity**:  
  37.23% of the students identify as BIPOC+, with a majority identifying as White. This showcases diversity but also highlights areas where outreach to underrepresented groups could be expanded.

## Future Enhancements

- Incorporate additional data from future cohorts to identify trends over time.
- Include metrics on completion rates and post-program employment outcomes for a deeper analysis of program effectiveness.
- Expand the analysis to look at correlations between education levels and employment outcomes.
