📄 README.md — Data Cleaning & Preprocessing (Internship Task 1)
🧹 1. Project Title

Data Cleaning & Preprocessing – Internship Task 1

📘 2. About the Project

This project is part of the Data Analyst Internship Task 1.
The objective is to clean a raw dataset by identifying data quality issues and correcting them using Excel-based preprocessing techniques.
After performing all necessary cleaning steps, the final dataset is structured, consistent, and ready for analysis, visualization, or further modeling.

🔍 3. Issues Identified in the Raw Dataset

During inspection of the original dataset, the following issues were identified:

Three completely empty columns (Unnamed: 7, Unnamed: 8, Unnamed: 9)

Age column contained "unknown" values and non-numeric text

Gender values were inconsistent (Male, MALE, female, FEMALE, etc.)

City names had spelling mistakes (e.g., "Hydrabad")

Signup dates used mixed formats (5/21/2024 vs 21-05-2024)

Column names were not consistent (spaces, uppercase letters)

Duplicate rows existed in the dataset

These issues affect the accuracy and reliability of any future data analysis.

🔧 4. Data Cleaning Steps Performed (Excel-based)
✔ 1. Removed Empty Columns

Deleted columns with no useful data:

Unnamed: 7

Unnamed: 8

Unnamed: 9

✔ 2. Standardized Column Names

Converted all column names to lowercase

Replaced spaces with underscores

Example: Signup Date → signup_date

✔ 3. Cleaned and Corrected the Age Column

Replaced "unknown" with blank

Converted the age column to numeric

Calculated the average age from valid records

Filled missing/invalid age values with the average age

Rounded the results to whole numbers

This ensures that all records contain a valid numeric age.

✔ 4. Standardized Gender Values

Different variations of gender entries were standardized:

Male, MALE, male → male

Female, FEMALE, female → female

This improves grouping and filtering accuracy.

✔ 5. Corrected City Names

Converted all city names to lowercase

Fixed spelling errors

"Hydrabad" → "hyderabad"

✔ 6. Converted Dates to a Single Format

The signup_date column contained mixed date formats.
All dates were converted to a standard format:

dd-mm-yyyy


This ensures accurate sorting and time-based analysis.

✔ 7. Removed Duplicate Records

Duplicate entries were identified and removed to maintain data integrity.

✔ 8. Exported Final Cleaned Dataset

All cleaned data was saved into the file:

cleaned_dataset.xlsx

📁 5. Files Included in This Repository
File Name	Description
original_dataset.csv	The raw dataset provided before cleaning
cleaned_dataset.xlsx	Final cleaned dataset after preprocessing
README.md	Documentation explaining the data cleaning process
🎯 6. Tools Used

Microsoft Excel

Data validation and cleaning techniques

Date formatting and text transformation

Duplicate detection and removal

👩‍💻 7. Author

Balaji D
Data Analyst Internship Participant
