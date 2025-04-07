# Healthcare Database Analysis 

# Overview

- This project contains SQL queries designed to analyze a healthcare database. 
- The dataset includes patient demographics, medical history, hospital admissions, billing details, and doctor performance metrics.
- The queries provide insights into patient statistics, billing trends, and hospital efficiency.

# Database Used
- Database Name: HOSPITAL_DB
- Main Table: HEALTHCARE

## SQL Queries Implemented

##  Basic Data Retrieval
- Retrieve all patient records.
- Count total number of patients.
- Identify duplicate patient names.
- Retrieve all details for specific patient names.

##  Patient Demographics and Statistics
- Count the number of male and female patients.
- Show unique blood types in the hospital.
- Show unique insurance providers.
- Show unique medical conditions in the hospital.

## Billing and Financial Analysis
- Calculate the total billing amount for all patients.
- Get the average age of admitted patients.
- Retrieve patients sorted by billing amount (highest first).
- Find the most expensive patient billing case.
- Calculate the total billing amount per insurance provider.
- Find patients whose billing amount is above the average.

## Admission and Discharge Analysis

- Find the most common admission type.
- Get the total number of admissions per month.
- Find patients who stayed for more than 10 days.
- Find patients who haven't been discharged yet.
- Find patients readmitted within 30 days.

## Doctor Performance Analysis
- Find the top 3 doctors who admitted the most patients.
- Find the doctor with the highest average billing per patient.
- Find the percentage contribution of each doctor’s patients to total admissions.

## Advanced Queries
- Rank patients by billing amount using RANK().
- Categorize patients based on age using CASE (Child, Adult, Senior).
- Rolling total of admissions per month (cumulative count over time).
- Find the most common medical condition by gender.
- Find patients whose age is above the average for their admission type.
- Rank patients based on their hospital stay duration.
- Identify patients with multiple hospital admissions.

## Database Compatibility
These queries are optimized for Microsoft SQL Server (MSSQL).
Minor modifications may be required for MySQL, PostgreSQL, or other databases.

# How to Use
- Ensure the HOSPITAL_DB database is available.
- Import the HealthCare.sql file into a SQL execution tool such as SQL Server Management Studio (SSMS).
- Run the queries to extract meaningful insights from the dataset.

# Contribution
- Contributions are welcome! 
- Improve existing queries for better performance.
- Add new queries for deeper insights.
- Report issues or suggest optimizations.
