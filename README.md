# Population-Health-Improvement-Initiative - Data-Integration-Analytics
This project demonstrates an end‑to‑end healthcare data integration and analytics workflow designed to support a Population Health Improvement Initiative focused on chronic conditions such as hypertension, diabetes, osteoarthritis, and high LDL cholesterol.
The goal is to build a clean, unified, trustworthy dataset by integrating information from:

✔ Electronic Health Records (EHR) — patient demographics + chronic condition status

✔ Pharmacy System — medication fills

✔ Lab Test Results — diagnostic test values

This project reflects real-world healthcare data engineering and analytics tasks performed by clinical data teams.

📁 Project Overview
Healthcare leadership requires accurate, consistent, and unified data to understand chronic disease patterns and improve population health outcomes.

This project focuses on:

✔ Cleaning and standardizing multi-source healthcare data

✔ Resolving inconsistencies across EHR, pharmacy, and lab systems

✔ Integrating datasets into a single analysis-ready table

✔ Running SQL queries to extract insights for population health management

The final deliverable is a structured analytics report summarizing the workflow, code, and outputs.

✅ Tasks Completed

Task 1 — Inspect Dataset Structure (Excel)

✔ Analyzed raw CSV files in Excel to understand:

✔ Number of rows and columns

✔ Data types (numeric, categorical, date fields)

✔ Initial data quality issues (missing values, inconsistent formats)

✔ This step ensured proper planning for downstream cleaning and integration.

Task 2 — Summarize Chronic Condition Data (Excel)
Performed descriptive analysis in Excel:

✔ Count of patients by chronic condition

✔ Distribution of demographics

✔ Quick checks for anomalies (duplicate IDs, invalid dates)

✔ Excel was used for fast initial exploration before deeper cleaning in Python.

Task 3 — Data Cleaning & Standardization using Python applied Pandas Libraries in Jupyter Notebook:

✔ Removed duplicate patient records

✔ Standardized gender values (M → Male, F → Female)

✔ Parsed and normalized date formats

✔ Cleaned inconsistent text fields

✔ Handled missing values across EHR, pharmacy, and lab datasets

✔ Produced a clean, unified dataset ready for SQL analysis.

Task 4 — SQL Analysis Using SQLite medical database and executed SQL queries (Python + Jupyter Notebook)

✔ Connected to a SQLite 

✔ Patients born before 1980

✔ Female patients with Type 2 Diabetes

✔ Lab tests joined with patient demographics

✔ Distinct patients with payer information

These queries support chronic disease monitoring and care coordination.

🧠 Key Objectives:

✔ Data Cleaning & Standardization:

Unified data from EHR, pharmacy, and lab systems

Ensured consistency across patient records

Prepared data for population health analytics

✔ Multi-System Data Integration:

Linked datasets using PatientID

Validated cross-system consistency

Produced a single analysis-ready dataset

✔ SQL-Based Clinical Insights:

Extracted patient-level insights

Analyzed chronic condition patterns

Supported leadership’s population health initiative

🛠 Tech Stack:

Excel — Initial Data Inspection & summary

Python — Pandas, Numpy

SQLite — SQL queries for clinical data analysis

Jupyter Notebook — Integrated workflow

Data Sources — EHR, pharmacy claims, lab test results

📈 Project Outcomes:

✔Delivered a clean, unified dataset ready for population health analytics
✔Improved data quality across three healthcare systems
✔Enabled leadership to analyze chronic disease patterns
✔Established a reproducible workflow for future analytics modules
