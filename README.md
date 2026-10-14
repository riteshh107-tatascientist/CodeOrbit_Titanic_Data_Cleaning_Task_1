# Titanic Dataset Cleaning and Analysis

## CodeOrbit Tech — Data Science Internship | Task 1

**Author:** Ritesh Kumar Singh

## Project Overview
This project demonstrates basic data cleaning and statistical analysis using Python and Pandas on the Titanic dataset.

## Objectives
- Inspect dataset structure and data types.
- Identify and handle missing values.
- Check for duplicate rows.
- Calculate basic statistics.
- Export a cleaned dataset.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Cleaning Steps
1. Loaded the Titanic CSV dataset.
2. Inspected rows, columns, and missing values.
3. Filled missing Age values using the median.
4. Filled missing Embarked values using the mode.
5. Replaced missing Cabin values with `Unknown`.
6. Checked and removed duplicate rows.
7. Saved the cleaned dataset as a separate CSV file.

## Files
- `CodeOrbit_Task1_Data_Cleaning.ipynb` — notebook and analysis.
- `CodeOrbit_Task1_Cleaning_Report.md` — detailed report.
- `CodeOrbit_Titanic_Cleaned.csv` — cleaned dataset.

## Results
The original dataset contained 891 rows and 12 columns. Missing values were present in Age, Cabin, and Embarked. No exact duplicate rows were found in the initial dataset.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install Pandas using `pip install pandas`.
3. Open the notebook.
4. Update the dataset path if required.
5. Run the cells in order.

## Learning Outcome
This project provided practice with missing-value handling, duplicate checking, basic statistics, and exporting cleaned data.
