# Churn Analysis 1

## Overview
This repository contains an exploratory analysis of customer churn for a fictional telecommunication company offering home phone and internet services. The dataset covers 7,043 customers located in California for Q3.

Churn analysis is crucial for understanding customer behavior and identifying reasons why customers leave. This project aims to uncover patterns and insights to help reduce churn and improve customer retention strategies.

## Dataset
The following files are used for the analysis:

1. **Customer_Info.csv**: Contains demographic details about the customers, such as age, gender, and tenure.
2. **Location_Data.csv**: Provides information on the geographical distribution of customers.
3. **Online_Services.csv**: Details customers' usage of online services, including streaming, backups, and device protection.
4. **Payment_Info.csv**: Includes payment method, billing cycles, and payment history.
5. **Service_Options.csv**: Lists the services subscribed to by customers, such as internet type and phone plans.
6. **Status_Analysis.csv**: Tracks customer activity and engagement.
7. **a_IBM Telco Customers Churn Datasets.csv**: A comprehensive dataset consolidating information for further reference.

## Objectives
- **Understand Customer Churn**: Identify factors contributing to customer churn.
- **Customer Segmentation**: Group customers based on shared characteristics to tailor retention strategies.
- **Predictive Modeling**: Develop models to predict customer churn based on historical data.

## Analysis and Methodology

### 1. Data Cleaning
- Handle missing values.
- Standardize column names for consistency.
- Verify data integrity and remove duplicates.

### 2. Exploratory Data Analysis (EDA)
- Demographics: Analyze the impact of age, gender, and tenure on churn.
- Services: Identify which services (internet, phone, or streaming) contribute to churn.
- Payments: Assess how payment methods and billing cycles correlate with churn rates.
- Geographic Insights: Understand churn trends across different regions in California.

### 3. Modeling
- Build machine learning models to predict churn.
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1 score.

## Tools and Technologies
- **Python**: For data processing, visualization, and modeling.
- **Pandas**: Data manipulation.
- **Matplotlib/Seaborn**: Visualization.
- **Scikit-learn**: Machine learning.
- **SQL**: Querying and integrating data.
- **Jupyter Notebook**: Interactive analysis.

## Key Insights
1. **High Churn Segments**: Customers using month-to-month contracts and those paying via electronic checks show higher churn rates.
2. **Service Utilization**: Customers with no internet service churn less.
3. **Demographics**: Senior citizens have a higher churn rate compared to younger customers.

## Folder Structure
```
Churn-Analysis-1/
├── data/
│   ├── Customer_Info.csv
│   ├── Location_Data.csv
│   ├── Online_Services.csv
│   ├── Payment_Info.csv
│   ├── Service_Options.csv
│   ├── Status_Analysis.csv
│   ├── a_IBM_Telco_Customers_Churn_Datasets.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   ├── modeling.ipynb
├── reports/
│   ├── insights_summary.pdf
│   ├── visualizations/
├── README.md
```

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/Noob-Py-Developer/Churn-Analysis-1
   ```
2. Navigate to the project directory and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks in the `notebooks/` folder to follow the analysis process.

## Acknowledgements
- IBM Telco Customer Churn Dataset.

## License
This project is licensed under the MIT License. See the LICENSE file for details.


