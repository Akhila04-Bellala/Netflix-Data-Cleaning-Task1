# Netflix-Data-Cleaning-Task1
# Netflix Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas.

## Dataset
- Source: Kaggle – Netflix Movies and TV Shows
- Original records: 8,807
- Original columns: 12

## Tools Used
- Python
- Pandas
- Google Colab

## Data Cleaning Steps
1. Loaded and explored the dataset.
2. Identified missing values.
3. Replaced missing values in director, cast, country, rating, and duration with "Unknown".
4. Preserved missing date_added values because the actual dates were unavailable.
5. Checked for duplicate rows. No duplicates were found.
6. Standardized column names.
7. Converted date_added into datetime format.

## Final Result
- Cleaned dataset exported as `netflix_titles_cleaned.csv`.
- All duplicate rows checked; none were found.
- 10 missing date_added values were retained.

## Files
- `netflix_titles_cleaned.csv` – Cleaned dataset.
- `Netflix_Data_Cleaning_Task1.ipynb` – Google Colab notebook containing the code.

## Conclusion
The Netflix dataset was cleaned and preprocessed using Python Pandas, making it more consistent and ready for further analysis.
