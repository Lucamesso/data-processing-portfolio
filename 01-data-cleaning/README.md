# Data Cleaning

## Project Overview
This project focuses on cleaning a synthetic e-commerce orders dataset.

## Objectives
- Identify and remove exact duplicate records.
- Detect missing values.
- Identify inconsistent and invalid data.
- Standardize inconsistent text values.
- Handle invalid dates appropriately.

## Data Cleaning Process
- Checked the dataset for duplicate records.
- Identified missing values in relevant columns.
- Corrected spelling inconsistencies in country and payment method fields.
- Converted order dates into a consistent date format.
- Preserved potentially meaningful negative values for further review.
- Kept missing and invalid values rather than making unsupported assumptions.

## Key Decisions
- Removed one exact duplicate record.
- Corrected "Itally" to "Italy".
- Standardized "Pay Pal" to "PayPal".
- Preserved negative quantities and prices for review.
- Converted the impossible date into a missing date value.

## Final Output
The cleaned dataset contains 35 rows and 8 columns.

The final file was exported in CSV format.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Notes
The dataset is synthetic and was created for portfolio demonstration purposes.
