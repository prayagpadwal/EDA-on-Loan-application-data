# Exploratory-Data-Analysis-EDA-

# Exploratory Data Analysis (EDA) on Loan Application Data

Introduction
In this project, we explored a dataset containing various attributes related to loan applications. The goal was to gain insights into the data, particularly focusing on the TARGET variable, which presumably indicates whether an applicant defaulted on a loan (1) or not (0).

Tasks Performed:
Data Loading and Overview: Loaded the dataset and performed an initial exploration to understand the types of data, number of columns, and general characteristics of the dataset.

Handling Missing Values:
Identified columns with missing values and their count.
Explored the relationship between missing values and the default rate.

Descriptive Statistics:
Calculated summary statistics for continuous variables like AMT_INCOME_TOTAL and AMT_CREDIT.
Examined the distribution of the TARGET variable to understand the imbalance in the dataset.

Categorical Variable Analysis:
Explored categorical variables like CODE_GENDER and NAME_CONTRACT_TYPE and their relation with the default rate.

Correlation Analysis:
Investigated the correlation between various FLAG_DOCUMENT_XX columns and the default rate.

Outliers Detection:
Identified outliers in continuous variables (AMT_INCOME_TOTAL, AMT_CREDIT) using both visualization and statistical methods.
Explored how outliers could potentially impact the default rate.

Visualization:
Used bar plots, histograms, and other visual tools to visualize the distribution of various features and their relationship with the default rate.

Tools Used:
Python
Pandas for data manipulation
Matplotlib and Seaborn for data visualization

Conclusion:
The EDA provided valuable insights into the data, revealing relationships between different features and the default rate. These insights are critical for any subsequent predictive modeling and for making informed decisions in the loan approval process.
