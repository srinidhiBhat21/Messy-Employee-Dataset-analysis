# Messy Employee Dataset – Data Cleaning using Python

URL; https://roadmap.sh/projects/clean-csv

## Project Overview
This project focuses on cleaning and preprocessing the Messy Employee Dataset from Kaggle using Python and Pandas.

The objective was to improve data quality by handling inconsistent formatting, incorrect data types, missing values, and other data-related issues.

## Dataset
- **Source:** [Messy Employee Dataset – Kaggle](https://www.kaggle.com/datasets/desolution01/messy-employee-dataset)
- **File:** `Messy_Employee_dataset.csv`

## Tools & Technologies
- Python
- Pandas
- KaggleHub
- Jupyter Notebook

## Tasks Performed

1. Loaded the dataset using Pandas.
2. Explored the dataset using `head()`, `info()`, `shape`, and `dtypes`.
3. Converted the `Join_Date` column from object to datetime using `pd.to_datetime()` with `errors='coerce'`.
4. Removed leading and trailing whitespaces from categorical columns.
5. Standardized text formatting using `.str.strip()` and `.str.title()`.
6. Checked for duplicate records using `duplicated()`.
7. Identified missing values using `isnull().sum()`.
8. Handled missing numerical values using median imputation.
9. Performed a final audit to check data types, missing values, duplicates, and dataset dimensions.

## Key Learnings
- Handling missing values in datasets.
- Converting columns into appropriate data types.
- Working with date and time columns.
- Standardizing inconsistent categorical data.
- Performing data quality checks using Pandas.

## Project Files
- `Missing_Employee_analysis.ipynb` – Jupyter Notebook containing the data cleaning process.
- `Cleaned_Employee_Dataset.csv` – Cleaned dataset (if exported).

## Conclusion
This project provided hands-on experience in data cleaning and preprocessing using Pandas. It helped me understand the importance of data quality before performing exploratory data analysis and generating meaningful insights.
