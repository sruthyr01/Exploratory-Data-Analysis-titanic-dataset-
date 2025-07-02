# Task2-Titanic dataset-Exploratory Data Analysis
This repository contains an in-depth Exploratory Data Analysis (EDA) of the Titanic dataset provided by Kaggle. The Titanic dataset is a classic example in data science used for binary classification tasks – predicting whether a passenger survived or not based on features like age, sex, class, fare, etc.
## ✅Objectives
1. Understand the dataset and its features
2. Perform data cleaning and handling of missing values
3. Generate descriptive statistics
4. Visualize relationships between variables
5.  Identify patterns and insights that may influence survival
## 📊 Dataset
The dataset used is from the [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic) competition.
## 🧼 Data Cleaning

- Handled missing values (`Age`, `Embarked`, `Cabin`)
- Converted categorical variables (`Sex`, `Embarked`, `Pclass`)
- Renamed `Survived` values: `0` → `No`, `1` → `Yes`
## 📈 EDA Insights

- **Sex**: Females had higher survival rates
- **Pclass**: 1st class passengers were more likely to survive
- **Age**: Younger passengers had slightly better survival odds
- **Fare**: Higher fare correlated with survival
## 🛠 Tools Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
