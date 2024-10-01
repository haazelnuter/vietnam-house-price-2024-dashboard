# Power BI Dashboard Project for Vietnam Houase Price 2024
This project demonstrates the end-to-end process of downloading a dataset from Kaggle, performing data cleaning, handling missing values, transforming data in Power Query, and visualizing the results in an interactive Power BI dashboard.
## Table of Contents
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Handling Missing Values](#handling-missing-values)
- [Transforming Data](#transforming-data)
- [Power BI Dashboard](#power-bi-dashboard)
- [Usage](#usage)
## Dataset
- The dataset used for this project is downloaded from [Kaggle](https://www.kaggle.com/).
- To download the dataset:
    1. Create a Kaggle account.
    2. Navigate to the dataset URL: [[Dataset Link](https://www.kaggle.com/datasets/nguyentiennhan/vietnam-housing-dataset-2024)]
    3. Download the dataset as a CSV file and place it in the `/content/vietnam_housing_dataset.csv` if you used Colab.
## Data Cleaning
The data cleaning process involves:
- Handling missing values :
    1. Categorical features : imputation using most frequent
    2. Numeric features : imputation using KNN
- Handling Outliers :
   1. Detect Outliers for numeric data : Detect Outliers using Z-Score, Detect Outliers using IQR
   2. Handle Winsorization : This keeps the outliers but reduces their influence by setting them to a more reasonable value
## Power BI Dashboard
The image below present dashboard
![image](https://github.com/user-attachments/assets/c7fc0fd8-6731-462f-b083-4bac255a4656)
