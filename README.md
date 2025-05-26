Task-1
Data cleaning and preprocessing

Files Included
marketing_campaign.xls — Original dataset
main.ipynb — Python script for data cleaning
cleaned_marketing_camapign.xls — Cleaned and processed dataset
README.md — Summary of what was done

---

Tools Used
Python 3.x
Pandas library

---

Cleaning Steps Performed
1. Loaded the original Excel file using Pandas.
2. Handled missing values by filling them with 'Unknown'.
3. Removed duplicate rows from the dataset.
4. Standardized text columns by converting them to lowercase and stripping extra spaces.
5. Converted date column ('Dt_Customer') to a proper datetime format ('dd-mm-yyyy').
6. Renamed all column headers to lowercase and replaced spaces with underscores.
7. Fixed numeric types, such as converting 'year_birth' to numeric.

---

Output
The final cleaned dataset is saved as:
cleaned_marketing_campaign
