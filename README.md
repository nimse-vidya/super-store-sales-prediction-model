# super-store-sales-prediction-model

A Machine Learning project that predicts sales using historical data from the Superstore dataset. The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model building, and model evaluation.

---

## 📌 Project Overview

The goal of this project is to build a machine learning model that can predict sales based on different factors such as:

- Product category
- Product sub-category
- Customer segment
- Region
- State
- Shipping mode
- Order date
- Quantity
- Discount
- Other relevant features

By analyzing historical sales data, the model attempts to identify patterns and relationships that can be used to estimate future sales.

---

## 🎯 Objectives

- Clean and preprocess the Superstore dataset
- Perform Exploratory Data Analysis (EDA)
- Identify important factors affecting sales
- Perform feature engineering
- Prepare categorical and numerical features
- Train machine learning models
- Evaluate model performance
- Predict sales for new/unseen data
- Generate useful business insights

---

## 📂 Dataset

The project uses the **Superstore Sales Dataset**, which contains information about orders, customers, products, shipping, sales, discounts, and regions.

### Important Features

| Feature | Description |
|--------|-------------|
| Order Date | Date when the order was placed |
| Ship Date | Date when the order was shipped |
| Ship Mode | Shipping method |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Segment | Customer segment |
| Country | Customer country |
| City | Customer city |
| State | Customer state |
| Region | Sales region |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product Name | Name of the product |
| Quantity | Number of products ordered |
| Discount | Discount applied to the order |
| Sales | Sales amount |

---

## 🔄 Machine Learning Workflow

### 1. Data Collection
The Superstore dataset is loaded into the Python environment using Pandas.

### 2. Data Cleaning

The dataset is checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Unnecessary columns
- Outliers
- Inconsistent values

### 3. Exploratory Data Analysis

EDA is performed to understand:

- Sales distribution
- Sales by category
- Sales by region
- Sales by customer segment
- Sales trends over time
- Impact of discounts on sales
- Top-performing products

### 4. Feature Engineering

New features can be created from existing data, such as:

- Year
- Month
- Day
- Quarter
- Shipping duration
- Encoded categorical variables

### 5. Data Preprocessing

The data is prepared for machine learning using techniques such as:

- Missing-value handling
- Label encoding / One-Hot Encoding
- Feature scaling
- Train-test splitting

### 6. Model Building

Different regression algorithms can be trained and compared, such as:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- Gradient Boosting
- XGBoost

### 7. Model Evaluation

The models can be evaluated using:

- MAE — Mean Absolute Error
- MSE — Mean Squared Error
- RMSE — Root Mean Squared Error
- R² Score

---

## 🧠 Model Prediction

The trained model takes relevant order and product information as input and predicts the expected sales value.

Example:

```text
Input:
Category       → Technology
Sub-Category   → Phones
Region         → West
Quantity       → 3
Discount       → 0.10

Predicted Sales → $XXX.XX
