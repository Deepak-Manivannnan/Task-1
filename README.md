# Task 1: Data Cleaning and Preprocessing

## Objective

The objective of this task was to clean and preprocess multiple real-world datasets by identifying and resolving common data quality issues such as missing values, incorrect data types, invalid records, inconsistent formats, and duplicate entries. The cleaned datasets were prepared for further analysis and reporting.

## Tools Used

* Python
* Pandas
* Jupyter Notebook

---

# Dataset 1: Customer Personality Analysis

## Cleaning Steps Performed

* Reviewed dataset structure, column information, and summary statistics.
* Summary statistics revealed birth years ranging from 1893 to 1996. Since the dataset was collected between 2012 and 2014, records with a birth year of 1893 correspond to customers aged around 120 years, indicating potential data quality concerns. These records were investigated and documented but retained due to insufficient evidence for removal.
* Standardized column names for improved consistency and readability.
* Converted the `dt_Customer` column from object type to datetime format.
* Identified missing values in the `income` column.
* Removed records containing missing income values due to the low percentage of missing data.
* Inspected categorical columns for inconsistencies.
* Removed invalid marital status categories (`Absurd` and `YOLO`).
* Checked for duplicate records.
* Performed final validation to verify data types and missing values.
* Exported the cleaned dataset.

---

# Dataset 2: Medical Appointment No-Shows

## Cleaning Steps Performed

## Summary

- Loaded and inspected the Medical Appointment No-Shows dataset.
- Reviewed dataset structure, column information, and summary statistics.
- Standardized column names for improved consistency and readability.
- Converted the `ScheduledDay` column from object type to datetime format.
- Converted the `AppointmentDay` column from object type to datetime format.
- Identified and removed four records where the scheduling date occurred after the appointment date, as these records violate the expected appointment workflow.
- Identified and removed one record containing a negative age value, as age cannot be less than zero.
- Checked for missing values across all columns and confirmed that no missing values were present.
- Inspected categorical columns and verified category consistency.
- Checked for duplicate records and confirmed that no duplicate records were present.
- Conducted final data quality validation to verify data types, missing values, and overall dataset consistency.
- Exported the cleaned dataset for future analysis.

---

# Dataset 3: Mall Customer Segmentation

## Cleaning Steps Performed

## Summary

- Loaded and inspected the Mall Customer Segmentation dataset.
- Reviewed dataset structure, column information, and summary statistics.
- Summary statistics indicated that the age, annual income, and spending score variables were within reasonable ranges, with no apparent data quality issues.
- Standardized column names for improved consistency and readability.
- Checked for missing values and confirmed that no missing data was present.
- Inspected categorical values in the gender column and verified category consistency.
- Checked for duplicate records and confirmed that no duplicate records were present.
- Conducted final validation to verify data types and overall dataset quality.
- Exported the cleaned dataset for future analysis and customer segmentation tasks.

---

# Dataset 4: Netflix Movies and TV Shows

## Cleaning Steps Performed

### Data Cleaning Summary

- Loaded and inspected the Netflix Movies and TV Shows dataset.
- Reviewed dataset structure, column information, and summary statistics.
- Removed leading and trailing whitespace from the `date_added` column.
- Converted the `date_added` column from object type to datetime format.
- Identified missing values across multiple columns.
- Removed records with missing values in `date_added`, `rating`, and `duration` due to their very low frequency.
- Replaced missing values in the `director`, `cast`, and `country` columns with `"Unknown"` to preserve a large portion of the dataset.
- Checked for duplicate records and confirmed that no duplicate records were present.
- Conducted final validation to verify data types, missing values, and overall dataset quality.
- Exported the cleaned dataset for future analysis.

---

# Dataset 5: Sales Export 2019–2020

## Cleaning Steps Performed

### Data Cleaning Summary

- Loaded and inspected the Sales Export 2019–2020 dataset.
- Reviewed dataset structure, column information, and summary statistics.
- Standardized column names by removing leading spaces and converting names to a consistent format.
- Converted the `order_value_eur` column from object type to numeric format.
- Converted the `date` column from object type to datetime format.
- Checked for missing values and confirmed that no missing data was present.
- Inspected categorical columns and verified category consistency.
- Checked for duplicate records and confirmed that no duplicate records were present.
- Conducted final validation to verify data types, missing values, and overall dataset quality.
- Exported the cleaned dataset for future analysis and reporting.

---

# Key Data Cleaning Techniques Applied

* Data type correction
* Missing value handling
* Invalid record removal
* Date format standardization
* Categorical value inspection
* Duplicate record detection
* Column name standardization
* Business rule validation
* Final data quality verification

---

## Outcome

Successfully cleaned and validated five real-world datasets by applying industry-standard data preprocessing techniques. The resulting datasets are consistent, reliable, and ready for further analysis and visualization.

