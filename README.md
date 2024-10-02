# Student Demographics Analysis

## Overview

This project explores the demographics of students applying to the **Tech Moms** program using application data. The dataset provides insights into the employment status, education levels, household income, and diversity of the applicants. Using Tableau, I visualized key trends such as employment categories, income distribution, and the representation of various racial and ethnic groups. The goal is to understand the applicant profile and support program decision-making for future cohorts.

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
- **Visualized the employment distribution** of the applicants.
- **Purpose**: Identify how many applicants are unemployed, part-time, or full-time to assess the need for career support.
- **Visualization Type**: Bar chart, labeled "Employment Status Breakdown."

#### Income Distribution (Sheet 2)
- **Visualized the household income** distribution of applicants.
- **Purpose**: Assess the financial backgrounds of applicants and identify income brackets.
- **Visualization Type**: Pie chart, labeled "Income Distribution."

#### Education Level Breakdown (Sheet 3)
- **Explored the education levels** of the applicants.
- **Purpose**: Understand the educational qualifications of the applicant pool, from high school to bachelor's degree.
- **Visualization Type**: Bar chart, labeled "Education Level Breakdown."

#### Diversity Representation (Sheet 4)
- **Displayed the racial and ethnic composition** of the applicants, focusing on BIPOC+ groups.
- **Purpose**: Analyze the diversity of the program's applicants.
- **Visualization Type**: Pie chart, labeled "Diversity Representation."

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
