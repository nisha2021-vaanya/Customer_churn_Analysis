Customer Churn Analysis
## Overview
This repository presents an exploratory data analysis (EDA) of customer churn for a telecom company. The analysis focuses on identifying patterns and key drivers of customer churn, leveraging visualization and Python-based data wrangling techniques
## Dataset
Source: The dataset contains records for 7,043 customers, with 21 features including demographic, service usage, and churn status information.
## Key Columns:
customerID, gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, Churn.
## Project Structure
Customer Churn.csv – Raw data file (not included here for licensing reasons).
Python scripts and Jupyter notebooks containing EDA steps.
Visualizations generated for each categorical/numerical feature.
This README.md file.
## Analysis Highlights
Data Cleaning: Converted blanks in TotalCharges to 0, cast data types, and replaced SeniorCitizen from 0/1 to 'no'/'yes' values.
No Missing/Duplicates: After cleaning, zero missing values and no duplicate rows were present.
Target Variable: 26.54% of customers have churned; 73.46% are retained.
## Churn Trends:
Gender: Churn evenly split between male and female customers.
Senior Citizens: Higher churn rate (41.7%) compared to non-seniors (23.6%).
Tenure: Most churn occurs in the first couple of months.
Contract Type: Month-to-month contracts see the highest churn rates.
Payment Method: Customers paying by electronic check are more likely to churn.
Services: Absence of online security, backup, tech support, or streaming increases churn risk.
## Visualizations
The analysis includes bar charts, count plots, pie charts, and histograms to illustrate:
## Churn distribution
Churn by gender, senior citizen status, contract, payment method, and tenure.
## Dependencies
Python (>=3.6)
pandas
matplotlib
seaborn
numpy
Jupyter Notebook
## Install dependencies with:
bash
pip install pandas matplotlib seaborn numpy
Usage
Clone the repository:
## text
git clone https://github.com/yourusername/customer-churn-analysis.git
Place the Customer Churn.csv dataset in the root directory.
Run the Jupyter notebook or scripts to reproduce the analysis and plots.
## Key Insights
Customers with short tenures, month-to-month contracts, or electronic check payments are at highest churn risk.
Providing more secure, bundled, or long-term service options may reduce churn rates.
## Project link 
https://github.com/nisha2021-vaanya/Customer_churn_Analysis/tree/main
