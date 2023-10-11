# BankCustomerSegmentation_EDA

## Introduction
This project combines Exploratory Data Analysis (EDA) with customer segmentation of a bank dataset. The initial phase involved EDA of customer data, followed by customer segmentation based on key attributes such as age, location, transaction history, frequency, and transaction amount. Profiles were created for each segment to better understand and serve the bank's customer base.

## Contents
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Used](#data-used)
- [Files in the Repository](#files-in-the-repository)
- [Tools Used](#tools-used)
- [Author](#author)

## Exploratory Data Analysis (EDA)
EDA, or Exploratory Data Analysis, is the process of examining and investigating a dataset to summarize its main characteristics. It involves tasks such as generating summary statistics, creating visualizations, and identifying patterns and relationships within the data. The primary goal of EDA is to gain a deep understanding of the dataset, uncover potential insights, and detect anomalies or data quality issues. EDA is an essential initial step in the data analysis process and is often used to inform subsequent analyses or decision-making.

## Data Used
The primary dataset used in this project is "bank_transactions.csv." You can find this dataset on Kaggle at [Kaggle Bank Transactions Dataset](https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation).

## Files in the Repository
- **[bank_transactions.csv](bank_transactions.csv)**: This is the main dataset.
- **[cleaned_data.csv](cleaned_data.csv)**: It contains data after removing nulls, changing necessary data types, and adding an age group column.
- **[transaction_data.csv](transaction_data.csv)**: Data grouped by customers, including transaction frequency, total amount, and month segmentation.
- **[EDA_BankCustomerSegmentation.ipynb](EDA_BankCustomerSegmentation.ipynb)**: In this Jupyter Notebook, customer segmentation is done based on age and location attributes.
- **[TransactionBehaviorSegmentation.ipynb](TransactionBehaviorSegmentation.ipynb)**: This Jupyter Notebook includes detailed segmentation analysis, creating segments and customer profiles based on transaction behavior.

## Tools Used
- **Programming Language:** Python
- **Libraries:**
  - **Pandas:** Used for data analysis and manipulation.
  - **Matplotlib:** Employed for data visualization.
- **Environment:**
  - **Jupyter Notebook:** Used for creating and running analysis notebooks.

## Author
- **Sai Manoj Pandiri**
