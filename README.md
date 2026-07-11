# Week 2 – EDA & Baseline Regression Modeling

## Project Overview

This project was completed as part of my AI/ML Internship Week 2 task.

The objective was to clean the dataset, perform Exploratory Data Analysis (EDA), engineer useful features, preprocess the data, and build baseline regression models for energy consumption prediction.

---

## Dataset

Industrial Energy Consumption Dataset

Target Variable:
- Usage_kWh

---

## Project Workflow

### 1. Data Preprocessing
- Loaded dataset
- Checked data types
- Removed duplicate values
- Checked missing values
- Converted date/time columns
- Handled outliers using IQR Method

---

### 2. Exploratory Data Analysis (EDA)

Visualizations created:

- Correlation Heatmap
- Boxplot
- Average Energy Consumption by Load Type
- Average Energy Usage by Hour

---

### 3. Feature Engineering

Created new features including:

- Power_factor_Ratio
- High_Load
- Hour
- Month
- Day Type

---

### 4. Data Encoding

Applied One-Hot Encoding on categorical columns.

---

### 5. Feature Scaling

Applied StandardScaler to normalize numerical features.

---

### 6. Machine Learning Models

The following regression models were trained:

- Linear Regression
- Ridge Regression
- Decision Tree Regressor
- Random Forest Regressor

---

## Model Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

The models achieved excellent performance with R² scores close to 0.99, indicating high prediction accuracy.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Author

Farhan Ali

AI/ML Intern
