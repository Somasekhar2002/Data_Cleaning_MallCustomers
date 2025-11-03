# Data_Cleaning_MallCustomers
Internship Task 1 -- Data cleaning using Excel on Mall Customers Dataset
# Task 1: Data Cleaning and Preprocessing

*Internship:* Data Analytics  
*Tool Used:* Microsoft Excel  
*Dataset:* Mall Customer Segmentation Data (Kaggle)

## Objective
Clean and prepare the dataset: handle missing values, remove duplicates, standardize text, fix data types and rename headers.

## Files
- Mall_Customers_RawData.xlsx — Original dataset (raw)
- Mall_Customers_Cleaned.xlsx — Cleaned dataset
- Cleaning_log.xlsx — Notes and count of changes made

## Steps Performed
1. Saved a working copy as Mall_Customers_Cleaned.xlsx.
2. Identified and removed 2 rows with missing critical values.
3. Removed 5 duplicate rows using Data → Remove Duplicates.
4. Trimmed extra spaces with TRIM() and replaced values using Paste Special → Values.
5. Standardized gender values (e.g., MALE → Male) using Find & Replace and PROPER() where needed.
6. Renamed headers to lowercase and underscore format (e.g., customer_id).
7. Saved the final cleaned file.

## Results
Dataset cleaned and ready for analysis. See Cleaning_log.xlsx for exact counts of removed rows and duplicates.
