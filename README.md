# Student-Depression-Analysis-Using-SQL-and-Tableau

## Project Objectives:
To analyze the factors contributing to depression among students using survey data. The aim is to identify correlations between depression levels and variables such as academic pressure, financial stress, study satisfaction, sleep duration, and study hours to gain insights that can help in improving student well-being.

## Dataset Used
-<a href="https://github.com/KirankumarB17/Student-Depression-Analysis-Using-SQL-and-Tableau/blob/main/Depression%20Student%20Dataset.csv">Dataset</a>

## Key Questions Addressed:
- How does academic pressure influence student depression?
- What is the relationship between financial stress and mental health?
- Does study satisfaction correlate with student well-being?
- What sleep duration is most common among students, and how does it affect their mental health?
- How do study hours impact students’ psychological status?

## Process Steps:
- Data Cleaning and Preprocessing (in SQL Server):
Removed null or blank gender entries.

Standardized gender entries from 'male'/'female' to 'M'/'F'..
Created an Age_Group column (A1: 18–24, A2: 25–30, A3: 31+)..
ransformed binary depression values from 1/0 to 'YES'/'NO'..
An index column was added to identify the rows uniquely..
Verified each categorical column for consistency using GROUP BY queries..

- Data Analysis (in Tableau):
Created individual charts for:

Financial Stress vs Student Count (Bubble chart)..
Academic Pressure vs Student Count (Square chart)..
Study Satisfaction vs Student Count (Bar chart)..
Sleep Duration vs Student Count (Pie chart)..
Study Hours vs Student Count (Area chart)..
Integrated all charts into a single dashboard for comprehensive analysis.

- Dashboard interaction <a href="https://github.com/KirankumarB17/Student-Depression-Analysis-Using-SQL-and-Tableau/blob/main/Final%20Dashboard.PNG">View Dashboard<a/>


## Dashboard
https://github.com/KirankumarB17/Student-Depression-Analysis-Using-SQL-and-Tableau/blob/main/Final%20Dashboard.PNG
