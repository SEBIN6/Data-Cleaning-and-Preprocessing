# Data-Cleaning-and-Preprocessing
Summary of Data Cleaning:
- Loaded dataset with 2240 rows and 29 columns.
- Handled 0 missing values in 'Income' by filling with median.
- Removed 2 duplicate rows.
- Standardized 'Marital_Status' and 'Education' to lowercase.
- Converted 'Dt_Customer' to 'dd-mm-yyyy' format.
- Renamed columns to lowercase with underscores.
- Ensured 'year_birth' as int, 'income' as float.
- Removed unrealistic values (negative income, year_birth < 1900).
- Final dataset: 2238 rows, 29 columns.
