#HR Analytics Dashboard – Power BI Project
##Introduction

This project focuses on building an interactive HR Analytics Dashboard using Power BI to analyze workforce demographics, employee retention, and attrition trends. The dashboard helps HR teams make data-driven decisions by identifying workforce patterns, high-risk segments, and key performance metrics.

#Data Preparation
##Data Loading

The dataset was imported into Power Query for cleaning and transformation.

##Data Quality Check

Verified data types

Ensured dataset contains no nulls or structural errors

##Column Removal

Removed unnecessary fields to optimize the data model:

Over18

StandardHours

EmployeeCount
##Calculated Columns

Created additional fields for segmented analysis:

Distance Group: 0–5 km, 6–10 km, 11–20 km, 20+ km

Monthly Income Bins

#Measures / KPIs

Developed using DAX:

Total Employees: 1470

Active Employees: 1233

Employees Left: 237

Attrition Rate: 16.12%

Average Tenure: 7 years

Average Age: 37

Average Salary: $6.50K

Average Job Satisfaction: 2.73

Average Environment Satisfaction: 2.73

Average Distance Travelled: 9 km

Attrition by Department: HR – 19.05%, R&D – 13.84%, Sales – 20.63%

Gender-wise Attrition: Male – 17.01%, Female – 14.08%

#Dashboard Features
##Pages

Workforce Overview

Employee Retention

Attrition Analysis

Drill-through Page for detailed employee-level insights

##Dynamic Measures

Two dynamic DAX measures were created:

Active Employees

Employees Left

These power the visuals:

Employees by Age Group & Gender

Employee Distribution Across Departments

Users can switch between workforce and attrition view with one click.

##Dynamic Titles

Dynamic DAX titles applied to visuals connected to dynamic measures, ensuring clarity when switching between Active vs Left employee metrics.
##Slicers & Navigation

Gender & Department slicers placed inside a Filter Button (via bookmarks) for a clean layout

Clear Filters button included

Custom icon-based page navigation created using bookmarks for smooth movement across pages

#Visual Design
##Bar Chart – Monthly Income by Job Role

Shows the average salary across job roles.
##Donut Charts – Marital Status & Overtime

Highlight workforce distribution and overtime participation.

##Column Charts – Job Satisfaction, Performance Rating, Environment Satisfaction, Work-Life Balance

Visualize employee feedback and workplace experience.

##Scatter Plot – Years at Company by Job Role

Displays employee tenure distribution across job roles.

##Matrix with Heatmap – Employees by Job Role & Attrition by Job Level

Shows employee distribution and attrition by job level.
Heatmap color intensity highlights high-density or high-risk roles.

##Area Charts – Employees by Distance Travelled & Attrition by Distance

Illustrate commuting distance patterns and attrition distribution.

##Line Chart with Trendline – Attrition by Age & Income

Shows attrition variations across age groups and income levels.

##Tree Map – Attrition by Job Role

Displays turnover distribution across roles.

##Drill-through Table – Employee Details

Provides employee-level metrics including:

Tenure

Department

Salary

Satisfaction Scores

Attrition Status

#Results
1. Workforce Composition

46% Married

32% Single

22% Divorced

Highest education backgrounds: Life Sciences (41%), Medical (32%)

2. Employee Distribution

Most active employees are aged 55+

Highest attrition in 55+ and 26–35 age groups

R&D has the highest workforce and attrition

3. Compensation & Tenure

Highest earners: Sales Executives

Longest tenure: Managers (14.4 years)

Shortest tenure: Sales Representatives (2.9 years)

4. Work Patterns

77% do not work overtime

Most employees rate environment & work-life balance as 3–4

Majority commute 0–5 km

5. Attrition Trends

Overall attrition: 16.12%

Under-20 age group has 67% attrition

20+ km commuters show 22% attrition

Highest attrition seen in Sales Representatives & certain HR/Lab Technician roles

#Tools Used

Power BI

Power Query

DAX

#Project Stages

Data Preparation

Measures & KPIs

Visual Design

Insights & Results
