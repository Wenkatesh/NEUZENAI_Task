# 🛒 Retail Demand Forecasting using Walmart Store Sales Data

## 📌 Overview

This project develops a machine learning-based demand forecasting system for Walmart retail stores using historical sales data and external factors such as holidays, promotional markdowns, weather conditions, fuel prices, CPI, unemployment, and store characteristics.

The objective is to accurately predict weekly sales, helping retailers optimize inventory management, reduce stock shortages, minimize overstock, and improve business planning.

---

## 🎯 Objectives

- Predict weekly sales for Walmart stores and departments.
- Analyze seasonal and holiday sales patterns.
- Engineer meaningful time-series and business features.
- Compare multiple machine learning models.
- Interpret model predictions using SHAP and LIME.
- Provide actionable business recommendations.

---

## 📂 Dataset

Dataset: Walmart Store Sales Forecasting (Kaggle)

Files Used:

- train.csv
- test.csv
- features.csv
- stores.csv

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- SHAP
- LIME
- Google Colab

---

## 🔄 Project Workflow

### 1. Data Loading

- Load Walmart datasets
- Merge train, features and stores datasets

### 2. Data Preprocessing

- Handle missing values
- Convert Date column
- Remove duplicates
- Validate data types

### 3. Exploratory Data Analysis

- Weekly sales trends
- Holiday analysis
- Store analysis
- Department analysis
- Correlation analysis

### 4. Feature Engineering

Created:

- Year
- Month
- Week
- Quarter
- Total Markdown
- Lag Features
- Rolling Mean
- Rolling Standard Deviation
- Store Average Sales
- Department Average Sales
- Interaction Features

### 5. Model Development

Implemented three forecasting models:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

### 6. Hyperparameter Tuning

RandomizedSearchCV was used to optimize XGBoost hyperparameters.

### 7. Model Evaluation

Metrics used:

- MAE
- RMSE
- WMAE
- MAPE
- R² Score

TimeSeriesSplit was used for model validation.

### 8. Model Explainability

Implemented:

- SHAP Summary Plot
- SHAP Feature Importance
- SHAP Waterfall Plot
- LIME Local Explanation

---

## 📊 Results

| Model | MAE | RMSE | WMAE | R² |
|------|------|------|------|------|
| Linear Regression | XX | XX | XX | XX |
| Random Forest | XX | XX | XX | XX |
| XGBoost | XX | XX | XX | XX |

XGBoost achieved the best forecasting performance and was selected as the final model.

---

## 📈 Business Insights

- Holiday weeks significantly increase sales.
- Promotional markdowns positively influence demand.
- Historical sales are strong predictors of future demand.
- Store characteristics impact weekly sales.
- Demand forecasting can improve inventory planning and reduce operational costs.

---

## 📁 Repository Structure

```
Retail-Demand-Forecasting-Walmart/
│
├── data/
├── images/
├── Walmart_Retail_Demand_Forecasting.ipynb
├── Process_Flow.pdf
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Retail-Demand-Forecasting-Walmart.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook Walmart_Retail_Demand_Forecasting.ipynb
```

---

## 📌 Future Improvements

- Deep Learning (LSTM/GRU)
- Prophet Forecasting
- LightGBM
- Real-time forecasting API
- Model deployment using Streamlit or FastAPI

---

## 👨‍💻 Author

**Madaparthi Venkatesh**

AI Engineer Technical Assignment
