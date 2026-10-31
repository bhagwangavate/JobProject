Job Market & Salary Analytics Dashboard

An interactive Power BI dashboard that explores the job market and salary trends across roles, skills, industries, locations, companies and experience levels. It is built to answer practical questions for job seekers, such as which roles pay the most, which skills are most in demand, and where are the jobs?

Dashboard Overview

<!-- Add a screenshot of each page to an /images folder and update the paths -->
Objectives
Understand overall job market size: total jobs, companies and locations
Compare salaries across job titles, experience levels, skills and employment types
Identify the most in-demand skills and how much they pay
Find the top hiring companies, industries and locations
Track job posting trends over time
Dashboard Pages
Page	What it shows
Overview	KPI cards: Total Jobs, Total Companies, Average Salary, Total Locations
Job Market Analysis	Jobs by Location, Jobs by Role, Average Salary by Experience
Salary Analysis	Median, Minimum and Maximum Salary, plus Average Salary by Job Title
Skills Analysis	Top 10 In-Demand Skills, Average Salary by Skill, Job Distribution by Industry, Jobs by Education Level
Company & Work Analysis	Top 10 Companies, Job Distribution and Average Salary by Employment Type, Job Posting Trends Over Time (Year → Quarter → Month → Day)
Dataset

Single table: job_market_salary_dataset

Column	Description
Job_ID	Unique job identifier
Job_Title	Role / position
Company	Hiring company
Industry	Industry of the employer
Location	Job location
Employment_Type	Type of employment (e.g. full-time, contract)
Experience	Experience level required
Education	Education level required
Skills	Skills required for the role
Salary	Salary offered
Posted_Date	Date the job was posted (with a Date Hierarchy)

Source: add your dataset source / link here (e.g. Kaggle).

DAX Measures
Total Jobs
Total Companies
Total Locations
Average Salary
Tools & Skills Used
Power BI Desktop: data modelling, DAX, interactive visuals
DAX: calculated measures
Visuals: donut charts, clustered bar/column charts, line chart, KPI cards
Data cleaning & transformation with sql Query
How to Use
Download Job_Market___Salary_Analytics.pbix
Open it in Power BI Desktop (free)
Use the page tabs at the bottom to move between the five report pages
Click any chart element to cross-filter the other visuals
Key Insights
<!-- Fill these in with what you actually see in your dashboard, for example: -->
Which job title has the highest average salary?
Which skills are most in demand, and which pay the most?
Which locations and industries have the most openings?
How does salary change with experience level?
Repository Structure
├── Job_Market___Salary_Analytics.pbix
├── README.md
└── images/
    ├── overview.png
    ├── job-market-analysis.png
    ├── salary-analysis.png
    ├── skills-analysis.png
    └── company-work-analysis.png
Author

Bhagwan Gavate Aspiring Data Analyst | Excel · SQL · Python · Power BI GitHub: bhagwangavate
