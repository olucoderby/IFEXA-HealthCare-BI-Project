# HealthCare Performance Dashboard

## Project Overview
This project was developed as a part of healthcare and data analytics portfolio project. 

The aim is to analyse the hospital's healthcare performance data and build an interactive POWER BI dashboard to help management understand 
- How the hospital is performing 
- ⁠what areas need attention
- ⁠where management can focus on how to improve the hospital standards 

The project covers data preparations, data modelling, DAX calculations, visualisation and business insights using Microsoft Power BI

# Business Questions

The dashboard was designed to help management have an idea on:

1. The total revenue the hospital generated across the various branches
2. The total number of patients across the various branches 
3. The monthly visits of patients
4. Which department receives the most patients?
5. Which department has the longest waiting time?
6. Which branch handles the most visits? 
7. Which age group represents the largest number of patients?
8. Which diagnoses are most common?
9. Which states have the highest patient volume?
10. How many patients are returning?
11. What are the most common patient outcomes?
12. what should the management focus on?

# Tools 
- Microsoft Excel
- Microsoft Power BI
- Power Query
- DAX
- GitHub

# Dataset
The dataset contains details about the hospital's performance and patients' experiences.

Key fields include:
- Revenue
- Profit
- Patients
- Visits
- Outcome
- Diagnoses
- State
- - Branch
- Service
- Age
- Gender 
- Department

# DAX Measures
- Total Revenue
- Total Cost
- Total Profit
- Profit margin %
- Average waiting time
- Average satisfactory score
- Age group
- Achievement target %
- Revenue variance
- Revenue target
- Previous month revenue

# Data Cleaning Process
- Confirm data types: dates as Date, age and visit count as Whole Number, revenue and cost as numeric, and categories as Text.
- Check for nulls, duplicates, invalid values and inconsistent category spelling.
- The uploaded workbook has 1,200 patient records, no missing cells in the patient table and no duplicate rows.
- Verify that revenue and cost are treated as numeric values, not text.
- Check that the date table covers the full reporting period and has a unique date for each day.

# Data Model
Use Patient_Visits as the central fact table. Use one-to-many relationships from each dimension to the fact table, create dimension tables:
- Date_Table
- DimState (including the state target and user access)

# Key Insights and Recommendations
— Lekki branch has the lowest patients satisfactory score despite relatively low waiting time compared to other branches. Management should look into patients feedback and services rendered like staffing, equipment functionality, etc.

— Pediatrics has the highest workload and profit
Pediatrics records 221 patients, 515 total visits and ₦3.71 million in profit, the highest among departments.
Management should review staffing, equipment and capacity against demand. Assess whether its waiting time of 46.37 minutes can be reduced without compromising care.

— Laboratory has the longest waiting time
Laboratory averages 46.97 minutes, the highest of the six departments.
Management should measure waiting time at each stage of the laboratory process and identify where delays occur before changing staffing or workflow.

— Rivers has the largest patient volume and revenue
Rivers has 322 patients, 804 total visits and ₦12.73 million in revenue.
Management should use Rivers as a benchmark for understanding demand and revenue performance, then check whether its cost structure and patient experience can be replicated elsewhere.

— Revenue target achievement is low across all states
Achievement ranges from 20.61% in Anambra to 27.47% in Abuja; overall achievement is 23.92%.
Management should validate the targets, investigate revenue capture and billing, and compare actual performance against the correct target period. The dataset alone does not explain the shortfall.

— Malaria and typhoid account for a large share of diagnoses
Malaria accounts for 283 patients and typhoid for 221; together they represent 42% of the patient records.
Management should review demand for testing, treatment and follow-up associated with these diagnoses, using clinical guidance and local public-health priorities.




