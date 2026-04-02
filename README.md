# Sales Forecasting 

##  Objective
The objective of this project is to build a machine learning model capable of predicting future sales based on historical data.  
This task was completed as part of my internship at Future Intern.

The goal is to help businesses:
- Understand sales trends  
- Anticipate future demand  
- Support better decision-making  

---

##  Tools & Technologies
- Python  
- Pandas & NumPy (data manipulation)  
- Matplotlib & Seaborn (data visualization)  
- Scikit-learn (machine learning models)

---
## Repository Structure

FUTURE_ML_01/
│
├── images/                         # Contains all generated visualizations and plots
│   ├── avg_sales_month.png         # Average sales per month (seasonality analysis)
│   ├── category_sales.png          # Total sales by product category
│   ├── complete_sales_forecast.png # Full forecast visualization (actual vs predicted sales)
│   ├── Evaluation_of_Models.png    # Comparison of model performance (MAE, RMSE, R², etc.)
│   ├── feature_correlation.png     # Correlation matrix of features
│   └── monthly_sales_trend.png     # Monthly sales trend over time
│
├── FUTURE_ML_01_Sales.ipynb        # Main notebook (EDA, feature engineering, modeling, forecasting)
│
└── README.md                      # this file
---

##  Project Workflow

### 1. Data Preprocessing
- Converted date columns  
- Handled missing values and duplicates  
- Filtered inconsistent data  

### 2. Exploratory Data Analysis (EDA)
- Analyzed sales trends over time  
- Identified seasonal patterns  
- Studied sales distribution by category and region  

### 3. Feature Engineering
- Created time-based features (Month, Quarter, Year)  
- Generated lag variables (Lag_1, Lag_3, Lag_12)  
- Computed rolling statistics (mean, standard deviation)  

### 4. Model Building
- Linear Regression  
- Random Forest  
- Gradient Boosting  

### 5. Model Evaluation
- MAE (Mean Absolute Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  
 

### 6. Forecasting
- Predicted sales on test data  
- Generated future sales forecast (next 6 months)  

---

## 📈 Business Insights

- Sales exhibit **seasonality**, with peaks during specific periods (especially Q4)  
- **Feature engineering** (lags & rolling averages) significantly improves prediction performance  
- **Linear Regression** performed best for this dataset  
- Discount strategies impact profitability and should be optimized  

---
## Dataset
Superstore Sales Dataset:https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

