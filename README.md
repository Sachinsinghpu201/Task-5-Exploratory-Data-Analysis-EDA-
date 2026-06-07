# 🚢 Task 5: Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the famous Titanic dataset. The objective is to understand the data, uncover hidden patterns, identify relationships between variables, detect anomalies, and generate meaningful insights through statistical summaries and visualizations.

EDA is a crucial step in the data science workflow as it helps build intuition about the dataset before applying machine learning models.

---

## 🎯 Objective

* Perform statistical exploration of the dataset.
* Analyze passenger demographics and survival patterns.
* Identify trends, correlations, and anomalies.
* Visualize distributions and relationships between features.
* Generate actionable insights from the data.

---

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📂 Project Structure

```
Task5_Titanic_EDA/
│
├── TASK5.ipynb           # Jupyter Notebook containing complete EDA
├── README.md             # Project documentation
├── Titanic.csv           # Dataset
└── Report.pdf            # Findings and observations report
```

---

## 📊 Exploratory Analysis Performed

### 1. Dataset Overview

* Loaded dataset using Pandas.
* Inspected dimensions, columns, and data types.
* Checked for missing values.
* Generated descriptive statistics.

Functions used:

```python
df.info()
df.describe()
df.isnull().sum()
```

---

### 2. Univariate Analysis

Analyzed individual feature distributions using:

* Histograms
* Countplots
* Boxplots

Features explored:

* Age
* Fare
* Passenger Class
* Gender
* Embarked Location

---

### 3. Bivariate Analysis

Studied relationships between variables:

* Survival vs Gender
* Survival vs Passenger Class
* Survival vs Age
* Survival vs Fare
* Passenger Class vs Fare

Visualizations:

* Bar Charts
* Scatter Plots
* Box Plots

---

### 4. Correlation Analysis

Generated correlation matrix and heatmap to identify relationships among numerical features.

Visualization:

```python
sns.heatmap()
```

---

### 5. Pairwise Relationship Analysis

Used pairplots to explore interactions among numerical features.

Visualization:

```python
sns.pairplot()
```

---

## 📈 Key Findings

### Gender and Survival

* Female passengers had significantly higher survival rates than male passengers.
* Women and children were prioritized during evacuation.

### Passenger Class Impact

* First-class passengers had the highest survival probability.
* Third-class passengers experienced the lowest survival rate.

### Fare Analysis

* Passengers paying higher fares generally had better chances of survival.
* Fare shows a positive relationship with passenger class and survival.

### Age Distribution

* Majority of passengers were young adults.
* Children showed comparatively better survival rates.

### Missing Values

* Age and Cabin columns contained missing data.
* Proper handling of missing values is essential before modeling.

### Correlations

* Passenger class and fare exhibited notable relationships.
* No extremely strong linear correlations among most numerical variables.

---

## 📊 Visualizations Included

* Histograms
* Countplots
* Boxplots
* Scatterplots
* Pairplots
* Correlation Heatmap
* Survival Comparison Charts

---

## 🔍 Summary of Findings

The EDA revealed that survival on the Titanic was heavily influenced by:

1. Gender
2. Passenger Class
3. Fare Amount
4. Age

Female passengers and first-class travelers had significantly greater survival rates. The analysis also highlighted missing values and feature relationships that are useful for future predictive modeling tasks.

---

## 🚀 Learning Outcomes

Through this project, the following skills were developed:

* Data Cleaning and Inspection
* Statistical Data Exploration
* Data Visualization
* Pattern and Trend Identification
* Correlation Analysis
* Insight Generation
* Reporting Findings

---

## 📚 Dataset Source

Titanic Dataset from Kaggle:

https://www.kaggle.com/c/titanic/data

---

## 👨‍💻 Author

Sachin Singh

Task 5 – Exploratory Data Analysis (EDA)
Data Analytics / Data Science Practice Project
