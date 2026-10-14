
# CodeOrbit Tech Internship
## Task 1: Data Cleaning and Exploration

### 1. Project Overview
Dataset: Titanic Passenger Dataset
Tool: Python, Pandas, NumPy
Original records: 891
Original columns: 12

### 2. Data Quality Findings
- Age: 177 missing values
- Cabin: 687 missing values
- Embarked: 2 missing values
- Exact duplicate rows: 0

### 3. Cleaning Steps
1. Created a copy of the original dataset.
2. Filled missing Age values with the median age.
3. Filled missing Embarked values with the most frequent category.
4. Replaced missing Cabin values with "Unknown".
5. Checked for duplicate rows and removed any exact duplicates.
6. Checked column data types and retained appropriate types.

### 4. Statistical Results
- Mean age after cleaning: 29.36 years
- Median age after cleaning: 28.00 years
- Mean fare: 32.20
- Median fare: 14.45
- Passengers who survived: 342
- Passengers who did not survive: 549
- Male passengers: 577
- Female passengers: 314
- First-class passengers: 216
- Second-class passengers: 184
- Third-class passengers: 491

### 5. Key Findings
- 342 of 891 passengers survived (approximately 38.4%).
- Third class was the largest passenger class.
- There were more male passengers than female passengers.
- The mean fare was higher than the median fare.

### 6. Conclusion
The dataset was inspected, cleaned and analyzed using Pandas.
Missing values were handled using documented decisions.
Statistical summaries were calculated, and the cleaned dataset
was saved separately for further analysis.

### 7. Files
- Original dataset: titanic.csv
- Cleaned dataset: CodeOrbit_Titanic_Cleaned.csv
