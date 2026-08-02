# Healthcare-Analysis-Dashboard
An interactive Power BI dashboard analyzing hospital patient data covering billing, insurance, bed occupancy, doctor feedback, and diagnosis trends to support data-driven healthcare decision-making
# Project Overview

This project explores a hospital dataset to uncover insights around patient billing, insurance coverage, bed utilization, and doctor performance. The goal was to design a single-page, interactive Power BI report that lets stakeholders (hospital admin, finance, or operations teams) quickly explore key metrics and filter data by patient or date range.

# Objectives
Track total billing amount and key patient dates (admit, discharge, follow-up) at a glance.
Analyze bed occupancy across the patient population.
Compare billing amount against health insurance amount by diagnosis.
Understand patient feedback volume across doctors.
Break down patient distribution by diagnosis type.
Enable interactive filtering by Patient ID and Admit Date.
# Tech Stack
Power BI Desktop — data modeling, DAX, visualization
Power Query — data cleaning and shaping
# Dashboard Features
Visual	Insight
KPI Cards	Total Billing Amount, Admit Date, Discharge Date, Follow-up Date
Column Chart	Patient count by Bed Occupancy
Donut Chart	Feedback volume per Doctor
Funnel Chart	Patient count by Diagnosis
Line Chart	Billing Amount vs. Health Insurance Amount by Diagnosis
Slicers	Filter by Patient ID and Admit Date range

(See screenshots below.)

# Repository Structure
├── Health_Care_Analysis_Dashboard.pbix   # Power BI dashboard file
├── screenshots/                          # Dashboard preview images
└── README.md
# Key Fields in the Dataset

Patient_ID, Admit_Date, Discharge_Date, Followup Date, Doctor, Diagnosis, Bed_Occupancy, Billing Amount, Health Insurance Amount, Feedback

# How to View
Download Health_Care_Analysis_Dashboard.pbix.
Open it in Power BI Desktop (free).
Use the slicers to filter by Patient ID or Admit Date and explore the visuals interactively.
# Skills Demonstrated
Data Cleaning & Modeling in Power BI / Power Query
DAX measures and aggregations
Dashboard design (KPI cards, funnel, donut, column, line charts)
Interactive filtering with slicers
Healthcare data analysis
# Future Improvements
Add patient demographic breakdowns (age, gender) if available in the source data.
Add a length-of-stay metric (Discharge Date − Admit Date).
Publish the report to Power BI Service for live web viewing.
Add drill-through pages for individual doctor or diagnosis performance.
# Author

Aryan

If you found this project useful or interesting, feel free to ⭐ the repository and connect with me!
