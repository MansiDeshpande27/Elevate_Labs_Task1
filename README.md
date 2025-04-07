# Elevate Labs - Task1
Task 1: Data Cleaning and Preprocessing

Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).

Tools: Python (Pandas)

Deliverables: Cleaned dataset + short summary of changes

Dataset name : Customer Personality Analysis

**SUMMARY**
1) Identify and handle missing values using .isnull() in Python or filters in Excel.

Income column had 24 null values. Since the Income column was not normally distributed, we used median instead of mean.

2) Remove duplicate rows using .drop_duplicates() or Excel’s “Remove Duplicates”.

There were no duplicate values in the dataset.

3) Standardize text values like gender, country names, etc.

Columns like marital status and education containing text values already had standardized values.

4) Convert date formats to a consistent type (e.g., dd-mm-yyyy).

Column "Dt_customer" was of object type which was converted to datetime.Further, "Dt_customer" column was used to create extra column called "Age" for future analysis.

5) Rename column headers to be clean and uniform (e.g., lowercase, no spaces).

Column names were renamed.

6)Check and fix data types (e.g., age should be int, date as datetime).

This is already done.

7) Unwanted columns that don't serve any purpose were removed.
