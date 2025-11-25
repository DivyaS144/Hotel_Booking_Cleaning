# Hotel Booking Data Cleaning & Exploratory Analysis

This project focuses on cleaning, preparing, and analyzing the Hotel Booking Demand dataset. The goal is to build a clean, structured dataset and extract meaningful insights through systematic EDA.

## Project Workflow

### 1. Data Loading
Imported the dataset and performed an initial structural check, including shape, column names, and missing values.

### 2. Data Cleaning
- Standardized column names  
- Handled missing values (children, agent, company, country)  
- Removed invalid rows (zero total guests)  
- Corrected data types (numeric, categorical, datetime)  
- Identified and removed ADR outliers using IQR  
- Removed duplicate rows  

### 3. Feature Engineering
Created new analytical fields:
- total_stay  
- total_guests  
- is_family  
- arrival_month_num  

### 5. Outputs
A fully cleaned and structured dataset ready for further analysis, visualization, or dashboarding.

## Tools and Libraries
- Python  
- Pandas  
- NumPy  
