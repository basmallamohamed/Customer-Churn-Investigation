# Telco Customer Churn Analysis

## Overview
This repository contains an analysis of the Telco Customer Churn dataset from Kaggle (https://www.kaggle.com/datasets/blastchar/telco-customer-churn?select=WA_Fn-UseC_-Telco-Customer-Churn.csv). The project explores customer churn patterns to prepare for future binary classification models.

## What I Did
- **Data Quality Check**: Inspected the dataset for duplicates and null values to ensure data integrity.
- **Pivot Tables**: Created pivot tables to calculate churn rates based on contract type, payment method, and tenure.
- **Imbalanced Data Detection**: Identified an imbalance in the dataset, with approximately 26.5% churned ('Yes') and 73.5% non-churned ('No') customers.
- **Visualizations**: Generated stacked bar charts to visualize churn rates across contract types and payment methods.

## Tools and Libraries
- **Python**: Version 3.9 or higher.
- **Pandas**: For data manipulation and pivot tables.
- **Matplotlib**: For creating visualizations.
- **Scikit-learn**: For handling imbalanced data (e.g., oversampling).

## Requirements
Install the required packages using the following command:
```bash
pip install -r requirements.txt
```
The `requirements.txt` file includes:
- `kagglehub==0.2.3`
- `pandas==2.2.2`
- `matplotlib==3.9.2`

## How to Run
1. Download the dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` from the Kaggle link.
2. Place it in the project directory.
3. Install the required libraries using the command above.
4. Run the Python script (e.g., `churn_analysis.py`) in a Python environment like Jupyter Notebook or Google Colab.

## Results
- No duplicates or null values were found.
- Pivot tables revealed higher churn rates for month-to-month contracts (~42%) and electronic check payments (~45%).
- The imbalance was noted, with potential for oversampling or other balancing techniques.
- Visualizations confirmed these patterns with clear stacked bar charts.

eed adjustments!
