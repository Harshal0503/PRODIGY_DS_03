# Prodigy InfoTech Data Science Internship - Task 3

## Project: Customer Purchase Prediction using Decision Tree Classifier

This repository contains the work for **Task 3** of my Data Science internship at **Prodigy InfoTech**. The primary objective was to build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data.

---

## 🔍 Overview
Predicting customer behavior is a core application of machine learning in business. This project utilizes a decision tree algorithm to create a model that classifies customers based on the likelihood of them subscribing to a term deposit, providing a clear visual representation of the decision-making process.

## 📊 Dataset
The dataset used for this project is the **Bank Marketing Dataset**, sourced from the UCI Machine Learning Repository.
* **Dataset Link:** [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
* **Description**: It contains data from direct marketing campaigns (phone calls) of a Portuguese banking institution.

## 🛠 Tools & Libraries
* **Python**: Core programming language.
* **Pandas & NumPy**: For data manipulation and feature engineering.
* **Matplotlib & Seaborn**: For visualizing class distributions and correlations.
* **Scikit-Learn**: For building the `DecisionTreeClassifier` and evaluating performance.
* **Google Colab**: Development environment.

## 🧹 Data Preprocessing
Key steps taken to prepare the data:
1. **Categorical Encoding**: Converted textual data into numerical format using Label Encoding to make it compatible with the Scikit-Learn classifier.
2. **Handling Imbalance**: Analyzed the distribution of the target variable to understand class frequency.
3. **Train-Test Split**: Divided the dataset into training (80%) and testing (20%) sets to ensure unbiased evaluation.

## 📉 Model Building
I implemented a classification model with the following steps:
* **Classifier**: Used `DecisionTreeClassifier` with the Gini impurity criterion.
* **Tree Visualization**: Generated a graphical representation of the tree to understand the decision-making logic and feature importance.
* **Evaluation Metrics**: Assessed the model using a Confusion Matrix, Accuracy Score, and a detailed Classification Report.

## 💡 Key Insights
* **Call Duration**: The duration of the last contact was a high-impact predictor; longer calls often correlated with successful subscriptions.
* **Previous Outcome**: Customers who were successfully contacted in previous campaigns were much more likely to subscribe again.
* **Demographics**: Specific age groups and job categories (e.g., students and retirees) showed distinct patterns in subscription rates.

---
