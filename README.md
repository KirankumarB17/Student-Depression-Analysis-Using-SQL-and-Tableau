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

- Dashboard interaction <a href="https://github.com/KirankumarB17/Student-Depression-Analysis-Using-SQL-and-Tableau/blob/main/Final%20Dashboard.PNG">View Dashboard<a/>

## Process Steps:
- Data Cleaning and Preprocessing (in SQL Server):
Removed null or blank gender entries.

Standardized gender entries from 'male'/'female' to 'M'/'F'..
Created an Age_Group column (A1: 18–24, A2: 25–30, A3: 31+)..
transformed binary depression values from 1/0 to 'YES'/'NO'..
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

## Dashboard

![Final Dashboard](https://github.com/user-attachments/assets/b8467713-43e1-4cc1-a29c-f4542aa62177)

## Project insight
##### Financial Stress:
- Highest student count (SC=110) at FS-1 (lowest financial stress level).,
Student count gradually decreases as financial stress increases.
##### Academic Pressure:
- Highest count (SC=125) at AP-3, suggesting moderate pressure might be more common or tolerable.,
Lower counts for high pressure levels.
- Study Satisfaction:
- Highest satisfaction (SS-4) has the highest student count (SC=116).,
Lowest satisfaction (SS-1) has the least count (SC=86), indicating dissatisfaction may correlate with fewer or more affected students.
- Sleep Duration:
- Balanced distribution.,
7–8 hours and more than 8 hours of sleep both show the highest student counts (SC=128 each), indicating optimal rest benefits mental health.
- Study Hours:
- Study hours vary widely.,
Highest concentration at 10 hours (SC=53), but overall, moderate study hours are most frequent.

