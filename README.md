# AI & ML Internship - Task 2: Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of the AI & ML Internship Task 2.

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset using Python and understand the data through statistics and visualizations.

## 🎯 Objective

The main objectives of this project are:

- Understand the structure of the dataset
- Generate descriptive statistics
- Identify missing values
- Analyze numerical feature distributions
- Detect potential outliers
- Study relationships between numerical features
- Identify patterns and trends in the data
- Analyze survival patterns

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset

The Titanic dataset contains information about passengers aboard the Titanic.

The dataset includes features such as:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## 🔍 EDA Performed

The following analysis was performed:

### 1. Dataset Understanding
- Checked dataset shape
- Examined column names
- Checked data types
- Identified missing values

### 2. Descriptive Statistics
Calculated:

- Mean
- Median
- Standard deviation
- Minimum
- Maximum
- Quartiles

### 3. Data Visualization

Created:

- Histograms
- Boxplots
- Correlation heatmap
- Pairplot
- Survival analysis charts

### 4. Outlier Detection

Used the Interquartile Range (IQR) method to identify potential outliers in numerical features.

### 5. Skewness Analysis

Calculated skewness for numerical features to understand the shape of their distributions.

### 6. Categorical Analysis

Analyzed survival patterns based on:

- Gender
- Passenger class

## 📈 Key Findings

- The dataset contains both numerical and categorical features.
- Missing values are present in Age, Cabin, and Embarked.
- Fare has a right-skewed distribution.
- Potential outliers can be observed in numerical features, particularly Fare.
- Survival patterns differ across gender and passenger class.
- The correlation matrix helps identify relationships between numerical features.

## 📁 Project Structure

```text
AI-ML-Internship-Task-2-EDA/
│
├── EDA_Titanic.ipynb
├── titanic_dataset.csv
└── README.md
