# Predicting-High-Income-Developers
Data Analytics and Machine Learning Mini Project
The dataset can be found here: https://survey.stackoverflow.co/
## 🧠 Predicting High-Income Developers
[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Data-Pandas-lightblue?logo=pandas&logoColor=black)](https://pandas.pydata.org/)  
[![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-orange?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/IDE-Jupyter%20Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)  

This project explores data from the 2024 Stack Overflow Annual Developer Survey to understand what factors contribute to a developer earning a high income.
It combines data analytics and machine learning techniques to:

**Explore developer demographics and work characteristics**

**Clean and preprocess real-world survey data**

**Build machine learning models to predict whether a developer earns above the median annual income**

## 🔍 Data Analytics Section

**The first part of the notebook focuses on data analytics and exploratory insights.**

Data Cleaning:

- Removed irrelevant or incomplete columns

- Handled missing values and outliers

- Standardised categorical values (e.g., education level, employment type)

Exploratory Data Analysis (EDA):

- Visualised age, education, and experience distributions

- Analysed correlations between skills, technologies, and compensation

- Created histograms, bar charts, and boxplots to explore relationships

Feature Engineering:

- Encoded categorical variables for modeling

- Created a binary target variable (HighIncome) based on the median of ConvertedCompYearly

## 🤖 Machine Learning Section

**The second half applies machine learning to classify developers into high-income vs. non-high-income groups.**

- Model Development

- Train/Test Split: Divided data into training and testing sets.

- Model Evaluation:

- Accuracy, precision, recall, and F1-score metrics

- Confusion matrix for performance visualisation

- Feature Importance Analysis: Identified which factors contribute most to higher income (e.g., experience, education, technologies used).


# 📈 Key Insights

- Certain programming languages and experience levels strongly correlate with higher salaries.

- Education plays a role but is less significant compared to practical experience.

- Machine learning models can predict income groups with a reasonable accuracy, with logistic regression and ensemble models offering the best accuracy.
