## **Project Overview**

This project performs Exploratory Data Analysis (EDA) on a mall customer dataset to understand customer demographics, spending patterns, and income distribution. The analysis includes both manual EDA techniques and automated profiling using the ydata-profiling library.

Dataset Information
The dataset contains the following columns:

CustomerID: Unique identifier for each customer

Gender: Customer gender (Male/Female)

Age: Customer age

Annual Income (k$): Annual income in thousands of dollars

Spending Score (1-100): Mall spending score (1-100 scale)

Analysis Performed
Data Cleaning
Missing value identification and handling

Removal of duplicate rows

Column renaming for consistency

Gender conversion to numeric values (Male: 1, Female: 0)

Exploratory Data Analysis
Basic statistics using describe()

Pairplot visualization of all numerical features

Gender distribution analysis

Correlation matrix of all features

Automated EDA
Comprehensive profiling using ydata-profiling

HTML report generation with detailed statistics and visualizations

Required Python packages:
pandas
seaborn
ydata-profiling


Key Findings
Dataset contains 200+ customer records with no missing values

Gender distribution is approximately balanced

Spending score shows interesting patterns when compared with age and income

Correlation analysis reveals relationships between different customer attributes

Output Files
Result.html: Comprehensive automated EDA report

Visualizations

Pairplot of all numerical features
Gender distribution chart
Correlation heatmap

Author
**Abhishek Modi**
