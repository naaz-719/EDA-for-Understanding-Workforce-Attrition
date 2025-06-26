# EDA for Understanding Workforce Attrition


# Description: 
This project presents a comprehensive Exploratory Data Analysis (EDA) of an HR dataset aimed at uncovering key patterns and trends in employee attrition. The dataset, sourced from Kaggle, contains detailed records about employee demographics, job roles, performance, compensation, and attrition status.

The main objective is to understand the factors contributing to employee turnover by examining the relationships between various features and attrition. This includes identifying high-risk groups, exploring salary patterns, analyzing job satisfaction, and uncovering any performance-related anomalies.

Using a combination of univariate and bivariate analysis techniques, the project investigates both individual variable distributions and interactions between key factors such as age, job role, income, performance rating, and overtime.

The insights gained from this EDA can support HR teams and recruiters in identifying retention strategies, optimizing compensation structures, and targeting areas that need intervention.


# Key Techniques:

📌 Univariate Analysis:
Countplots and barplots for categorical features (e.g., Gender, Job Role, OverTime)

Boxplots and histograms for numeric features (e.g., Age, MonthlyIncome)

Descriptive statistics (mean, median, standard deviation)

📌 Bivariate Analysis:
Attrition analysis by Gender, Job Role, and Overtime using grouped visualizations

Boxplots comparing attrition across numeric features (e.g., Income, Age)

Correlation matrix to highlight inter-feature relationships



# Outlier Detection:
Interquartile Range (IQR) method for detecting and removing salary outliers

Visualization of salary distributions with and without outliers for clarity





# Outcomes:
Identified job roles and departments with higher attrition rates

Highlighted that younger employees and those working overtime tend to leave more

Uncovered salary disparities and performance patterns linked to attrition

Cleaned dataset by handling outliers to improve data reliability for modeling


# Technologies Used:
Python (Pandas, NumPy)

Matplotlib and Seaborn for visualization

Jupyter Notebook for interactive data exploration
