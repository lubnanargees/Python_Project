# Python_Project
# Employee Data Analysis Project

## Overview
This project involves analyzing employee data from ABC Company to derive insights about workforce distribution, salary expenditure, and key trends. The dataset contains **458 rows and 9 columns**, covering details such as employee position, team, salary, age, and height. The primary goal is to **preprocess the data, perform in-depth analysis, and visualize key findings**.

## Preprocessing Steps
- The "Height" column contained inconsistent or missing values. It was replaced with **random values between 150 and 180** for standardization.
- Data integrity and consistency were ensured before performing analysis.

## Analysis Tasks
1. **Employee Distribution by Team:**
   - Counted the number of employees in each team.
   - Calculated the percentage split relative to the total workforce.
2. **Employee Segregation by Position:**
   - Counted the number of employees in each job position.
3. **Predominant Age Group:**
   - Grouped employees into predefined age brackets to identify the most common age range.
4. **Salary Expenditure Analysis:**
   - Determined which team and job position had the highest total salary expenditure.
5. **Correlation Between Age and Salary:**
   - Analyzed whether there was a relationship between an employee’s age and salary.

## Graphical Representations
To effectively visualize insights, the following plots were generated:
- **Bar Plot of Employee Distribution by Position** – Displays the number of employees per role.
- **Bar Plot of Predominant Age Group** – Shows the most common age group in the company.
- **Bar Plot of Salary Expenditure by Team** – Highlights teams with the highest payroll expenditure.
- **Bar Plot of Salary Expenditure by Position** – Illustrates positions with the highest salary allocation.
- **Scatter Plot of Age vs. Salary Correlation** – Depicts whether salary increases with age.

## Key Insights
- The workforce is **not evenly distributed** across teams, with some departments having significantly more employees than others.
- Certain job roles dominate the organization, while others have fewer employees.
- The majority of employees fall within the **25-34 age group**, indicating a young workforce.
- Salary expenditure is **highest for specific teams and positions**, likely senior leadership or revenue-generating departments.
- There is a **moderate to strong positive correlation** between **age and salary**, suggesting salary growth with experience.

## Conclusion
This analysis provides valuable insights into **workforce structure, salary allocation, and employee demographics**. The findings can help **optimize resource distribution, ensure fair compensation, and improve workforce planning**.

---
### Usage Instructions
To run this analysis in **Jupyter Notebook**, ensure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```
Then, execute the provided Python script to generate the **preprocessing steps, analytical insights, and visualizations**.

