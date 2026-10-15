***Titanic Dataset — Data Cleaning and Preparation***

**Project Overview**

This project focuses on cleaning and preparing the Titanic passenger dataset using Python and Pandas. The objective is to improve data quality before performing data analysis.

**Tools Used**

- Python
- Pandas
- Jupyter Notebook
- Excel/CSV

**Dataset**

The dataset contains passenger information such as passenger class, survival status, name, sex, age, ticket, fare, cabin, and embarkation port.

**Data Quality Issues Identified**

- Missing values in age, fare, cabin, embarked, boat, body, and home.dest.
- Duplicate records were checked.
- Column data types were inspected.
- Categorical values were checked for inconsistencies and unnecessary whitespace.

**Cleaning Performed**

1. Created a working copy to preserve the original dataset.
2. Filled missing age values with the median age (28.0).
3. Filled the missing fare value with the median fare (14.4542).
4. Filled missing embarked values with the mode (S).
5. Checked duplicate rows; no exact duplicates were found.
6. Removed leading and trailing whitespace from text columns.
7. Retained columns with substantial missing values rather than inventing values or deleting them without justification.
8. Validated the cleaned dataset.

**Validation Results**

- Final dataset size: 1,310 rows and 14 columns.
- Exact duplicate rows: 0.
- Missing values in age, fare, and embarked: 0.
- Remaining missing values: cabin, boat, body, and home.dest.

**Output Files**

- "titanic_cleaned.csv" — cleaned dataset in CSV format.
- "titanic_cleaned.xlsx" — cleaned dataset in Excel format.
- "Data_Cleaning.ipynb" — notebook containing the cleaning and validation steps.

**Conclusion**

This project demonstrates basic data-cleaning skills, including missing-value handling, duplicate checks, data-type inspection, text standardization, and data validation using Python and Pandas.