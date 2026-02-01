# Prodigy InfoTech Data Science Internship - Task 2

## Project: Titanic Dataset Exploratory Data Analysis (EDA)

This repository contains the work for **Task 2** of my Data Science internship at **Prodigy InfoTech**. The primary objective was to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset to identify patterns and factors that influenced passenger survival.

---

## 🔍 Overview
The Titanic project is a classic data science challenge. This analysis focuses on understanding the relationship between passenger features (like age, gender, and socio-economic class) and their survival outcome.

## 📊 Dataset
The dataset used is the **Titanic Dataset** from Kaggle, which contains information about 891 passengers, including:
* **Survived**: 0 = No, 1 = Yes
* **Pclass**: Ticket class (1st, 2nd, 3rd)
* **Sex**: Gender
* **Age**: Age in years
* **SibSp**: # of siblings / spouses aboard
* **Parch**: # of parents / children aboard
* **Fare**: Passenger fare
* **Embarked**: Port of Embarkation

## 🛠 Tools & Libraries
* **Python**: Core programming language.
* **Pandas**: For data manipulation and cleaning.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For creating static, animated, and interactive visualizations.
* **Google Colab**: Development environment.

## 🧹 Data Cleaning
Key steps taken to prepare the data:
1. **Handled Missing Values**: Filled missing 'Age' values with the median and 'Embarked' with the mode.
2. **Feature Selection**: Dropped the 'Cabin' column due to an excessive number of null values.
3. **Data Formatting**: Converted categorical variables into a format suitable for analysis.

## 📈 Exploratory Data Analysis
I explored several variables to see how they impacted survival:
* **Gender Analysis**: Comparison of survival rates between males and females.
* **Class Analysis**: Distribution of survival based on passenger class.
* **Age Distribution**: Understanding which age groups were most likely to survive.
* **Correlation Heatmap**: Visualizing the relationships between all numerical features.

## 💡 Key Insights
* **Gender**: Female passengers had a significantly higher survival rate than males.
* **Class**: Passengers in 1st class were prioritized and had the highest survival percentage.
* **Family Size**: Passengers traveling with small families had a better survival rate than those traveling alone or with very large families.
