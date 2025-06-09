# Titanic Survival Analysis

This project performs exploratory data analysis (EDA), feature engineering, and visualization on the Titanic dataset to understand factors influencing passenger survival.

## Overview

The analysis includes:

- Data cleaning and missing value handling  
- Feature engineering (Family Size, Age Groups, Encoding categorical variables)  
- Univariate, bivariate, and multivariate analysis  
- Outlier detection and treatment  
- Interactive and advanced visualizations  
- Statistical tests to assess relationships between features and survival  

## Libraries Used

- **NumPy:** For numerical operations and handling arrays efficiently  
- **Pandas:** For data manipulation and analysis  
- **Matplotlib:** For static visualizations  
- **Seaborn:** For enhanced statistical data visualization  
- **Scikit-learn (LabelEncoder):** For encoding categorical features  
- **SciPy:** For statistical testing  
- **Plotly Express:** For interactive and dynamic visualizations  

## Key Findings

- Gender, passenger class, and age significantly affect survival rates.  
- Females and 1st class passengers had higher survival probabilities.  
- Outliers were detected in Age and Fare; log transformation was applied to Fare.  
- Chi-square tests confirmed significant associations between survival and categorical features like Sex, Pclass, and Embarked.
## Dataset

The dataset used is the classic Titanic dataset available on Kaggle:  
[Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

## Author

Purnakam Shrivastava

