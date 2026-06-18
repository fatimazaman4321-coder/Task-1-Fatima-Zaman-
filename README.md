# Project 1: E-Commerce Data Cleaning - Decode Lab Internship
 🧹 Project Overview
This is Project 1 of my Decode Lab Internship. The objective was to clean and prepare raw e-commerce sales data for analysis. The dataset contained 1200 order records that required formatting fixes and standardization before EDA.
🎯 Cleaning Objectives
- Handle missing values in the `Coupon` column
- Add consistent currency formatting to monetary columns  
- Standardize text categories and date formats
- Remove duplicate order entries
- Prepare clean dataset for EDA in Project 2
 🛠️ Tools & Techniques Used
  Microsoft Excel: Format Cells, Find & Replace, Filters, Text to Columns
- Functions Used: TRIM, PROPER, IF, ISBLANK
- Quality Checks: Conditional Formatting, PivotTables for validation
 🔧 Cleaning Steps Performed
1. Missing Value Treatment
- Coupon Column: Replaced blank cells with `"No Coupon"` to maintain data consistency
- Verified all other critical columns like Order ID, Unit Price, Quantity had complete data
 2. Data Formatting & Standardization
- Currency Formatting: Added `$` dollar sign to `Revenue` and `Unit Price` columns for clarity. Values were previously numeric without currency symbols
Dates: Converted all order dates to consistent DD-MM-YYYY format
Text Categories: Used TRIM + PROPER to fix extra spaces and inconsistent casing in Payment Method & Marketing Channel
Category Cleanup: Standardized values: `creditcard` → `Credit Card`, `online payment` → `Online`
3. Duplicate Handling
- Used Remove Duplicates feature on Order ID to delete exact duplicate records
- Checked for negative values in `Quantity` and `Unit Price` columns
4. Final Validation
- Created PivotTables to confirm no blanks in key analysis columns
- Verified data types are correct: Dates as Date, Revenue as Currency, Text as Text
- Ensured dataset is analysis-ready for Project 2

 📁 Deliverables
File: `project_1_decodelab.xlsx` 
📊 Impact
Added proper currency formatting and handled coupon blanks to ensure the dataset is professional and ready for business analysis. This prevents confusion during EDA in Project 2.

👩‍💻 Author
**Fatima Zaman**  
Data Analysis Intern @ DecodeLab  
---
*This project demonstrates proficiency in Excel data cleaning, formatting, and data quality assurance.*# Task-1-Fatima-Zaman-
Project for DecodeLab internship 
