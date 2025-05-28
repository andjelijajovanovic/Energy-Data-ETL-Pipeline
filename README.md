# Energy Data ETL Pipeline

This project automates the manual quarterly data cleaning process for energy sales and capabilities, previously performed by analysts. The pipeline is designed to run monthly and helps deliver faster insights.

## Objective

To automate the data extraction, transformation, and loading (ETL) process for two raw datasets:
- `electricity_sales.csv`
- `electricity_capability_nested.json`

## Key Tasks

- Clean and structure `electricity_sales.csv`, which includes:
  - Parsing and standardizing fields such as `period`, `state`, `sector`, and `price`
- Flatten nested JSON structure from `electricity_capability_nested.json`
- Generate clean, analysis-ready outputs for data consumers
- Use data dictionary to understand and validate field types

## Technologies Used

- Python
- pandas
- JSON/CSV handling
- Jupyter Notebook

## Output

- Transformed and cleaned data in CSV and/or Parquet format
- Reproducible ETL notebook (`notebook.ipynb`)

