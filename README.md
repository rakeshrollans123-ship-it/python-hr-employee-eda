# HR Employee Exploratory Data Analysis (Python)

Exploratory data analysis of an HR employee dataset using **pandas**. It profiles salary and training hours, then looks at links between performance, experience, absence and attrition across departments and locations.

## Dataset
`HR_Employee_AnalysisReady (2).csv`, an analysis-ready HR file. Columns used: Salary, Training_Hours, Department, Location, Performance_Rating, Experience_Years, Attrition, Absence_Days. Add the CSV to the same folder as the script to run it.

## What the Script Does
1. Loads the data and prints its shape
2. `describe()` on salary and training hours
3. Employee counts by department; location mix as proportions
4. Correlations: training hours vs performance rating, experience vs salary
5. Cross-tabs: attrition by department (counts) and by location (percentages)
6. Group summaries: average salary and rating by department; average training hours and absence days by location

## Skills
Python · pandas · Descriptive statistics · Correlation · Cross-tabulation · GroupBy

## Usage
```bash
pip install pandas
python Rakesh_Python_Practical_6.py
```
