# Data Cleaning Task
This repository contains the solution for Task 1: Data Cleaning and Preprocessing using the [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis) dataset.

## Objective
Clean and preprocess a raw dataset by handling missing values, duplicates, inconsistent formats, and incorrect data types.

## Tools
- Python (Pandas)
- Google Colab
- Dataset: `marketing_campaign.csv`

## Steps Performed
1. Identified and filled missing 'Income' values with median using `.isnull()`.
2. Removed duplicates using `.drop_duplicates()`.
3. Standardized 'Marital_Status' and 'Education' to lowercase.
4. Converted 'Dt_Customer' to 'dd-mm-yyyy' format.
5. Renamed columns to lowercase with underscores.
6. Ensured 'year_birth' as int, 'income' as float.
7. Removed unrealistic values (negative income, year_birth < 1900).

## Files
- `clean_data.py`: Python script for cleaning.
- `cleaned_marketing_campaign.csv`: Cleaned dataset.
- `cleaning_summary.txt`: Summary of changes.
- `marketing_campaign.csv`: Original dataset (optional).

## How to Run
1. Upload `marketing_campaign.csv` to Google Colab (`/content/`).
2. Run `clean_data.py` in a Colab notebook.
3. Outputs: `cleaned_marketing_campaign.csv` and `cleaning_summary.txt`.

## Notes
- Dataset path in Colab: `/content/marketing_campaign.csv`.
- Outputs are saved in `/content/`.
