# Titanic Survival Analysis

This project aims to analyze the survival rates of passengers aboard the Titanic, focusing on how passenger class and age impact survival outcomes. The analysis also investigates whether certain passenger categories are more vulnerable during the disaster, using SQL, Python, Tableau, and Power BI for data analysis and visualization.

## Project Overview

The Titanic dataset provides key details about passengers, such as class, age, sex, and survival status. The goal of this project is to identify significant patterns and insights related to survival rates and explore how different factors such as passenger class and age categories affected survival chances.

## Objectives

- **Analyze Survival Rates by Passenger Class**: Investigate how the class of the passenger (first, second, or third) impacted survival chances.
- **Age and Vulnerability**: Assess how age categories (children, adults, seniors) influenced the survival rates within each passenger class.
- **Dashboard Visualization**: Create interactive dashboards using Tableau and Power BI to visualize the findings and make the data more accessible.

## Key Findings

- First-class passengers had significantly higher survival rates than third-class passengers.
- Children in second-class had a 100% survival rate, while children in third-class had a lower survival rate.
- Seniors in the first class had a low survival rate (only one survivor), while no seniors survived in second and third classes.
  
## Tools Used

- **SQL**: Data extraction and transformation from the Titanic dataset.
- **Python**: Data analysis, cleaning, and statistical analysis.
- **Tableau**: Visualization of the survival rate analysis across various passenger classes and age groups.
- **Power BI**: Interactive dashboard for real-time insights into the data.

## Files and Links

- **Tableau Dashboard**: [[Link to Tableau Dashboard](https://public.tableau.com/views/TITANICI_TABLEAUDASHBOARD/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]
- **Power BI Dashboard**: [[Link to Power BI Dashboard](https://drive.google.com/file/d/1WwwgLoHHD0FbENjD7L2pAwN-O_R3HRDu/view?usp=drive_link)]

## Steps Involved

1. **Data Collection and Cleaning**: The raw dataset was cleaned and processed to ensure accuracy. Missing values were handled, and irrelevant columns were removed.
2. **SQL Queries**: Key SQL queries were executed to extract necessary data points, including survival rates by class and age.
3. **Python Analysis**: Python was used for deeper analysis, including calculating survival rates and performing statistical analysis on age and class categories.
4. **Visualization**: The insights were visualized using Tableau and Power BI for an interactive user experience.
5. **Dashboard Creation**: Power BI and Tableau dashboards were developed to present the findings in a user-friendly way.

## Goal

The goal of this project is to examine if the survival rate had anything to do with the passenger class aboard the Titanic. Additionally, the analysis seeks to assess the age of passengers within each class to identify vulnerable age categories and determine how these factors affected the chances of survival.

## Assessment

The data analytics dashboard reveals significant differences in survival rates among various passenger classes on the Titanic. When examining survival percentages, a substantial disparity is evident. First-class passengers had almost three times the survival rate compared to third-class passengers. This highlights the importance of analyzing survival percentages rather than merely the total number of survivors.

- **First-Class Passengers**: The survival rate for first-class passengers is approximately 60%. When considering the percentage of survivors within each class, the rate is notably higher, emphasizing the critical need to differentiate between overall survival rates and class-specific survival percentages.
  
- **Age Impact on Survival**: Age also played a significant role in survival outcomes. Second-class children had a 100% survival rate, compared to 80% for first-class and 40% for third-class children. 
- No seniors survived in the second and third classes, while only 17% (one individual) survived in the first class. It is essential to conduct a deeper statistical analysis for the first-class result to determine if this survival rate among seniors is statistically significant or due to chance.

## Key Insights

- **Passenger Class Disparity**: A substantial disparity exists in the survival rates among different passenger classes. First-class passengers had significantly better survival chances compared to third-class passengers.
  
- **Vulnerable Age Groups**: Age proved to be a critical factor in determining survival. Vulnerable groups such as children and seniors were affected differently depending on the passenger class.

## Recommendations

- **Minimize Class Disparity**: Focus on minimizing the survival disparity between passenger classes through better emergency preparedness and accessibility measures.
  
- **Emergency Accessibility Measures**: Investigate accessibility measures to ensure that all age categories, regardless of class, have equitable opportunities for survival during an emergency.

- **Further Statistical Analysis**: Use the insights from this analysis to conduct deeper statistical analysis that will inform the design of ships to ensure more equitable safety protocols across all passenger classes and age categories.

## Next Steps

- Perform further analysis to confirm the statistical significance of the findings, especially the survival rate among seniors in first class.
- Explore how emergency accessibility measures could improve survival rates across all passenger classes and age groups.

## How to Run the Project

1. Download the dataset and run the SQL queries in your preferred SQL environment (e.g., SQL Server, MySQL, or PostgreSQL).
2. Use the provided Tableau and Power BI links to view the dashboards.

## Conclusion

The Titanic Survival Analysis project provides valuable insights into how passenger class, age, gender, and other factors influenced survival rates during the disaster. Through SQL queries and data visualizations in Tableau and Power BI, we identified significant disparities in survival rates across different passenger classes, with first-class passengers having the highest survival rates. Age played a crucial role, as children in second-class had a 100% survival rate, while seniors had the lowest survival rates, especially in third-class. 

The analysis highlights the need for further statistical studies to examine factors such as the impact of gender, the effects of lifeboat accessibility, and the relationship between class and emergency response. The findings suggest that the Titanic tragedy could have been mitigated with more equitable safety measures and better evacuation protocols, particularly for vulnerable age groups and lower-class passengers. 

Ultimately, this project demonstrates the importance of data analysis in understanding historical events and can serve as a foundation for designing future systems that prioritize safety and equity for all individuals, regardless of their status or age.
