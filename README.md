# Titanic Data Preprocessing and Outlier Analysis

This repository contains my first internship task, where I performed a complete preprocessing pipeline on the Titanic dataset. It includes handling missing data, encoding categorical features, normalizing numerical values, and detecting & removing outliers using boxplots and the IQR method.


## Dataset
Dataset used: **Titanic Dataset**  
You can download it from [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data) or use any Titanic `.csv` file.


##  Task Objectives

- 📌 Import and explore the dataset (data types, null values)
- 📌 Handle missing values using median/mode
- 📌 Convert categorical features into numerical (encoding)
- 📌 Normalize/standardize numerical features
- 📌 Visualize outliers using boxplots
- 📌 Remove outliers using the IQR method


##  Techniques Used

| Step                         | Method Used                           |
|------------------------------|---------------------------------------|
| Missing Values Handling      | Median (for Age), Mode (for Embarked) |
| Encoding Categorical Data    | One-Hot Encoding                      |
| Feature Scaling              | StandardScaler                        |
| Outlier Detection            | Boxplots (Seaborn)                    |
| Outlier Removal              | IQR (Interquartile Range)             |


##  Libraries Used

- Pandas
- Seaborn
- Matplotlib
- Scikit-learn

##  Sample Output

- Boxplots before and after removing outliers
- Shape of data before and after cleaning
- A clean, ready-for-ML dataset 



