
# 🌾 Seasonal Agriculture Performance Analysis

## 📌 Project Overview

Agricultural performance varies across seasons due to changes in environmental conditions, farming practices, resource availability, crop characteristics, and economic factors.

This project analyzes a dataset containing **4,000 agricultural records and 28 features** to identify seasonal patterns, relationships, variations, and performance differences.

The project combines **Data Analytics, Statistical Analysis, Data Visualization, and Machine Learning** to understand agricultural productivity and support data-driven seasonal planning.

---

## 🎯 Objectives

- Analyze agricultural performance across different seasons.
- Compare crop yield and production across seasons.
- Study the influence of environmental conditions on agriculture.
- Analyze soil and nutrient characteristics.
- Evaluate irrigation methods and water efficiency.
- Compare seasonal revenue, cost, and profit.
- Analyze disease and pest risk.
- Apply statistical hypothesis testing.
- Develop an Agricultural Performance Index (API).
- Predict crop yield using Machine Learning.
- Generate insights and recommendations for agricultural planning.

---

## 📊 Dataset

The dataset contains **4,000 records and 28 features** covering:

- Farm information
- State and district
- Crop and season
- Farm area
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil characteristics
- Nutrient usage
- Irrigation methods
- Fertilizer and pesticide usage
- Seed quality
- Crop yield
- Production
- Market price
- Cost and revenue
- Profit
- Water usage
- Water efficiency
- Disease and pest risk

---

## 🔍 Analysis Performed

### 1. Data Cleaning & Preprocessing
- Missing value analysis
- Duplicate record detection
- Data type verification
- Feature organization
- Preparation of data for statistical and ML analysis

### 2. Exploratory Data Analysis
- Crop-wise analysis
- State-wise analysis
- Seasonal comparisons
- Distribution analysis
- Relationship analysis

### 3. Seasonal Productivity Analysis
- Average yield
- Total production
- Average production
- Number of farms

### 4. Economic Analysis
- Revenue
- Production cost
- Profit
- Profit margin
- Seasonal economic comparison

### 5. Environmental Analysis
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil moisture

### 6. Soil & Nutrient Analysis
- Soil pH
- Soil moisture
- Nitrogen
- Phosphorus
- Potassium
- Fertilizer usage

### 7. Irrigation & Water Analysis
- Irrigation method comparison
- Water usage
- Water efficiency
- Relationship between water usage and yield

### 8. Disease & Pest Risk Analysis
- Seasonal disease/pest risk
- Risk variation across agricultural conditions

### 9. Statistical Analysis
ANOVA hypothesis testing was performed to examine whether seasonal differences in:

- Yield
- Profit
- Water efficiency

were statistically significant.

### 10. Agricultural Performance Index

A project-defined **Agricultural Performance Index (API)** was developed by combining:

- Yield
- Profit
- Water efficiency
- Resource efficiency
- Disease/pest risk

This provides an integrated measure for comparing agricultural performance.

---

## 🤖 Machine Learning

Machine Learning models were developed to predict:

### Target Variable
`Yield_Tonnes_Ha`

### Models Evaluated

- Linear Regression
- Random Forest Regression
- Gradient Boosting Regression

The models were evaluated using:

- MAE
- RMSE
- R² Score

Feature importance analysis was also performed to identify variables contributing to yield prediction.

---

## 📈 Visualizations

The project includes visualizations such as:

- Seasonal yield comparison
- Seasonal profit comparison
- Water efficiency comparison
- Disease and pest risk
- Crop performance
- Environmental analysis
- Irrigation analysis
- Correlation heatmap
- Agricultural Performance Index
- Machine Learning model evaluation
- Feature importance
- Actual vs predicted yield

---

## 🛠️ Technologies Used

| Category | Technologies |
|---|---|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Plotly |
| Statistics | SciPy |
| Machine Learning | Scikit-learn |
| Development Environment | Google Colab |
| Version Control | GitHub |

---

## 📁 Project Structure

```text
seasonal-agriculture-performance-analysis/
│
├── Dataset/
│   ├── agricultural_dataset.csv
│   └── README.md
│
├── Notebook/
│   ├── Agriculture_Performance_Analysis.ipynb
│   └── README.md
│
├── Results/
│   ├── Seasonal_Average_Yield.png
│   ├── Seasonal_Average_Profit.png
│   ├── Water_Efficiency.png
│   ├── Correlation_Heatmap.png
│   ├── Agricultural_Performance_Index.png
│   ├── Feature_Importance.png
│   └── Actual_vs_Predicted_Yield.png
│
├── Documentation/
│   └── README.md
│
├── README.md
└── requirements.txt
