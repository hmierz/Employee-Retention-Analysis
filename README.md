# Employee-Retention-Analysis
This project analyzes an HR Employee Retention dataset to explore factors related to turnover and satisfaction. It demonstrates descriptive statistics, z-scores, hypothesis testing, correlations, and regression in Python using a Jupyter or Google Colab notebook.

## Dataset
Variables expected in the dataset:
- satisfaction_level
- last_evaluation
- number_project
- average_monthly_hours
- time_spend_company
- Work_accident
- left
- promotion_last_5years
- department
- salary

Public source with a matching schema:
Kaggle HR Analytics Data Set  
https://www.kaggle.com/datasets/giripujar/hr-analytics

This repository includes a small sample file named hr_sample.csv for quick demos. To reproduce full results, download the full dataset from the source and use it with the notebook.

## How to Run

Google Colab
1. Open the notebook in Google Colab.  
2. Upload hr_sample.csv using the left file panel.  
3. Run all cells.  
4. To use the full dataset, upload the full CSV and set DATA_FILE = "your_full_dataset.csv" in the notebook.

Local Jupyter
1. Install dependencies: pip install notebook pandas matplotlib seaborn scipy statsmodel
2. Start Jupyter
3. Open .ipynb file and run all cells
4. 
## Methods Covered
- Descriptive statistics and visualization
- Z-score computation
- Independent samples t-test
- Mann-Whitney U test for ordinal salary
- Chi-Square test of independence
- Spearman correlation
- Simple linear regression

## Key Findings
- Employees with lower satisfaction are more likely to leave
- Higher average monthly hours are associated with turnover
- Salary level and work accidents show significant associations with retention
- Last evaluation has a small but significant positive effect on satisfaction
