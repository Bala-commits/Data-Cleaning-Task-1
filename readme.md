Data Cleaning & Preprocessing – Internship Task 1

1. About the Project
This project is part of the Data Analyst Internship Task 1.
The objective is to clean a raw dataset by identifying data quality issues and correcting them using Excel-based preprocessing techniques.
The final cleaned dataset is ready for analysis, reporting, and visualization.

2. Issues Identified in the Raw Dataset
The following issues were identified during inspection:
Three completely empty columns (Unnamed: 7, Unnamed: 8, Unnamed: 9)
age column contained "unknown" and non-numeric values
Gender values were inconsistent (Male, female, MALE, FEMALE, etc.)
City names had spelling mistakes (e.g., "Hydrabad")
Mixed date formats (5/21/2024 and 21-05-2024)
Column names contained spaces and inconsistent casing
Duplicate records existed

3. Data Cleaning Steps Performed (Excel-based)
Step 1: Removed Empty Columns
Deleted columns containing no useful data:
Unnamed: 7
Unnamed: 8
Unnamed: 9

Step 2: Standardized Column Names
Converted all column names to lowercase
Replaced spaces with underscores
Example:
Signup Date → signup_date

Step 3: Cleaned and Corrected Age Column
Replaced "unknown" with blank
Converted entire column to numeric
Calculated the average age
Filled missing/invalid ages with the average age
Rounded values to whole numbers

Step 4: Standardized Gender Values
Converted all gender values to lowercase
Standardized all variations into:
male
female

Step 5: Corrected City Names
Converted all city names to lowercase
Fixed spelling mistake:
"Hydrabad" → "hyderabad"

Step 6: Standardized Date Format
The signup_date column was converted into a single uniform format:
dd-mm-yyyy

Step 7: Removed Duplicate Records
Checked for duplicates and removed them to maintain data integrity.

Step 8: Exported Final Cleaned Dataset
The cleaned dataset was saved as:
cleaned_dataset.xlsx

4. Files Included in This Repository
File Name	Description
original_dataset.csv	Raw dataset before cleaning
cleaned_dataset.xlsx	Final cleaned dataset after preprocessing
README.md	Documentation of the entire cleaning process

 5.Tools Used
Microsoft Excel
Data validation techniques
Text and numeric cleaning
Date formatting
Duplicate removal

6. Author
Balaji D
Data Analyst Internship Participant
