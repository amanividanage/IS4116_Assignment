Overview

This project focuses on analyzing a diabetes dataset to understand the relationships between various health indicators and diabetes outcomes. The analysis involves data cleaning, exploratory data analysis (EDA), statistical analysis, and regression modeling to derive business insights and implications.
The dataset can be accessed via: https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes 

This dataset contains a diverse range of health-related attributes, meticulously collected to aid in the development of predictive models for identifying individuals at risk of diabetes. 
Data Selection

The dataset contains various health-related features such as glucose levels, insulin, BMI, and skin thickness, along with an outcome variable indicating whether a person has diabetes (1) or not (0). 

**Analytical Process
**
1. Data Preprocessing

Handling Missing Values: Replaced zeros in key health-related columns (e.g., Glucose, Insulin, BMI) with NaN and then imputed missing values using the mean.

![image](https://github.com/user-attachments/assets/f71409cd-f770-4a46-b59e-3db46441dfe4)
![image](https://github.com/user-attachments/assets/49711c89-7342-4637-93fb-eebc210f9b32)



2. Univariate Analysis

Examined the distribution of individual features (Glucose, Insulin, BMI, etc.).

Identified skewness and outliers that might affect predictive modeling.
![image](https://github.com/user-attachments/assets/49e31efa-0630-4b9b-a62a-3c9868134335)


3. Bivariate Analysis

Conducted scatter plots (e.g., Glucose vs. Insulin, Glucose vs. SkinThickness) to visualize correlations.

Used hue (Outcome variable) to distinguish diabetic vs. non-diabetic individuals.

4. Regression Analysis

Performed multiple linear regression to determine the strength of relationships between independent variables and the diabetes outcome.

Evaluated feature importance in predicting diabetes risk.


