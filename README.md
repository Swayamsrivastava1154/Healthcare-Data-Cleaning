# Healthcare-Data-Cleaning
Overview

This project focuses on cleaning and preprocessing healthcare data using Pandas and SciPy. The script ensures data quality by handling missing values, removing duplicates, detecting outliers, and standardizing data formats.

Features

1. Data Loading
Reads raw healthcare data from a CSV file.
Handles encoding issues to prevent errors.
2. Data Cleaning
Duplicate Removal: Eliminates duplicate records.
Missing Value Handling: Fills missing numerical values with column means.
Date Formatting: Converts date columns to proper datetime format.
Text Standardization: Converts categorical values like "Gender" to lowercase for consistency.
3. Outlier Detection
Uses Z-score normalization to detect and remove outliers in numerical columns.
4. Data Export
Saves the cleaned dataset as cleaned_healthcare_data.csv.
Technologies Used

Python (for scripting)
Pandas (for data manipulation)
SciPy (for statistical analysis)
