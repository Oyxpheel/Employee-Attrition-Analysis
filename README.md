Employee Attrition Analysis — ABC Manufacturing Ltd

AnalystLab Africa — Data Science Internship Programme Week 1: Business Understanding & Data Exploration

Project Overview

This project investigates employee attrition at ABC Manufacturing Ltd (a fictional client used for this exercise), using the IBM HR Analytics Employee Attrition & Performance dataset. As a Junior Data Scientist on the consulting team, the goal was to understand the company's workforce, identify patterns linked to employee turnover, and surface which variables could be useful for a future predictive attrition model.

Dataset
Source: IBM HR Analytics – Employee Attrition & Performance (Kaggle)
Size: 1,470 rows × 35 columns
Target variable: Attrition (Yes/No)
Business Questions Explored
What does the company's workforce look like?
Which departments have the highest employee attrition?
Does age influence attrition?
Does monthly income affect retention?
Does overtime influence attrition?
Which job roles experience the highest turnover?
Which variables appear important for future predictive modelling?
Tools & Libraries
Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook
Key Findings
Overtime is one of the strongest factors linked to attrition — employees who work overtime leave at roughly 3x the rate (~30%) of those who don't (~10%).
Monthly Income shows a clear gap between leavers (median ~₦3,200) and stayers (median ~₦5,200); high earners rarely leave.
Job Role shows the widest spread of all variables examined — Sales Representatives have an attrition rate of ~40%, compared to ~2.5% for Research Directors.
Department shows a moderate relationship: Sales and HR have the highest attrition rates (~19–20%), while R&D has the highest raw number of departures but the lowest rate (~13.5%), since it's the largest department.
Age shows only a weak relationship with attrition — leavers skew slightly younger (median 32 vs. 36), but the two groups overlap substantially.

Based on these findings, OverTime, MonthlyIncome, and JobRole appear to be the strongest candidate features for a future predictive attrition model.

Repository Contents
File	Description
Employee_Attrition.ipynb	Full analysis notebook — data loading, inspection, visualizations, and interpretations
Business_Understanding_Report.docx	Background on attrition, its business impact, and how data science supports HR decisions
Dataset_Inspection_Report.docx	Summary of dataset structure, data types, missing values, and duplicates
Reflection_Report.docx	Reflection on the learning process and possible next steps
Author

Fatimah Odumuyiwa Data Science Intern, AnalystLab Africa LinkedIn · GitHub

This project was completed as part of the AnalystLab Africa Data Science Internship Programme (Week 1 assignment).
