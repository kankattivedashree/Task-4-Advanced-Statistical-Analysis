# Task 4: Statistical Analysis, Time Series Analysis, Customer Segmentation & Predictive Modeling

## Project Overview

This project analyzes the Superstore Sales dataset to extract business insights using statistical methods, time series analysis, customer segmentation, and machine learning. The objective is to understand sales patterns, identify customer segments, and build a predictive model for profit.

---

## Dataset

**Dataset:** Superstore Sales Dataset

The dataset contains information about:

- Orders
- Customers
- Products
- Sales
- Quantity
- Discount
- Profit
- Order Date
- Shipping Details
- Region and Category

---

## Technologies Used

- Python 3.12
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

## Project Workflow

### 1. Data Loading & Exploration

- Imported dataset
- Checked data types
- Identified missing values
- Generated descriptive statistics

---

### 2. Statistical Analysis

Performed:

- Mean
- Median
- Standard Deviation
- Skewness
- t-Test
- Chi-Square Test
- 95% Confidence Interval

Purpose:
- Understand data distribution
- Compare customer segments
- Analyze relationships between categorical variables

---

### 3. Time Series Analysis

Converted **Order Date** into datetime format and performed:

- Monthly Sales Aggregation
- Monthly Sales Trend Visualization
- 3-Month Moving Average

Purpose:
- Identify sales trends over time
- Observe seasonality and business growth

---

### 4. Customer Segmentation

Applied K-Means Clustering using:

- Sales
- Quantity
- Discount
- Profit

Steps:

- Data Standardization
- Elbow Method
- K-Means Clustering
- PCA Visualization
- Cluster Profiling

Purpose:
- Group customers/products with similar purchasing behavior

---

### 5. Predictive Modeling

Built a Linear Regression model to predict **Profit** using:

Features:

- Sales
- Quantity
- Discount

Evaluation Metrics:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

Purpose:
- Predict future profits
- Understand the influence of business variables

---

## Results

Successfully completed:

- Statistical Analysis
- Time Series Analysis
- Customer Segmentation
- Predictive Modeling
- Business Insights

---

## Business Insights

- Sales trends were analyzed using monthly aggregation.
- Customer segments were identified using K-Means clustering.
- Discount has a significant impact on profitability.
- Sales is one of the strongest predictors of profit.
- The predictive model provides useful estimates for business decision-making.

---

## Project Structure

```
Task4/
│
├── AdvancedStatisticalAnalysis.ipynb
├── SampleSuperstore.csv
├── README.md
```

---

## How to Run

1. Clone this repository.

```bash
git clone <repository-link>
```

2. Install dependencies.

```bash
pip install pandas numpy matplotlib scipy scikit-learn
```

3. Open Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells in **Task4.ipynb**.

---

## Future Improvements

- Hyperparameter tuning for machine learning models
- Forecasting using ARIMA or Prophet
- Interactive dashboards using Power BI or Tableau
- Advanced customer segmentation techniques

---

## Author

Vedashree

Task 4 – Data Analysis & Machine Learning Project