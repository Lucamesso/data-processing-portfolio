# Data Validation

## Project Overview
This project focuses on checking the quality and consistency of a synthetic e-commerce orders dataset before further data analysis.

## Objectives
- Identify missing values and duplicate records.
- Check numeric values against expected rules.
- Validate date formats and date values.
- Verify categorical values against predefined lists.
- Identify unusual or potentially incorrect records.

## Data Validation Process
- Checked for missing values.
- Checked for duplicate order IDs and duplicate rows.
- Verified that IDs were present and positive.
- Checked quantity and price values against validation rules.
- Identified invalid and impossible dates.
- Checked product, country and payment method values against predefined lists.
- Identified unusually high prices for further review.

## Key Findings
- One missing quantity value was identified.
- Three invalid dates were detected.
- One invalid payment method was identified.
- One unusually high price was flagged for review.
- Negative quantities and prices were identified as potential anomalies.

## Validation Approach
The original dataset was not modified.

Anomalies were reported rather than automatically corrected, because their meaning and appropriate treatment require additional information.

## Final Output
A validation summary was generated in Word format, documenting the checks performed and the anomalies identified.

## Tools Used
- Python
- Pandas
- Jupyter Notebook
- Python-docx

## Notes
The dataset is synthetic and was created for portfolio demonstration purposes.
