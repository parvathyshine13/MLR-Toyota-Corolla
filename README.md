# Multiple Linear Regression Analysis on Toyota Corolla Dataset

## Project Overview
This project aims to predict the **price** of Toyota Corolla cars based on various features using multiple linear regression (MLR). The objective is to explore the dataset, build regression models, interpret their results, and evaluate their predictive performance. Additionally, regularization techniques such as Lasso and Ridge regression are applied to enhance model robustness and handle multicollinearity.

---

## Dataset Description
The dataset contains the following variables:

| Feature        | Description                             |
|----------------|---------------------------------------|
| Age            | Age of the car in years                |
| KM             | Total kilometers driven (odometer)    |
| FuelType       | Fuel type (Petrol, Diesel, CNG)       |
| HP             | Horsepower                            |
| Automatic      | Transmission type (Yes=1, No=0)       |
| CC             | Engine Cylinder Volume (cc)            |
| Doors          | Number of doors                       |
| Weight         | Weight of the car in kilograms         |
| Quarterly_Tax  | Quarterly road tax (Euros)             |
| Price          | Offer price in Euros (target variable) |

---

## Analysis Workflow

### 1. Exploratory Data Analysis (EDA)
- Loaded and inspected the dataset for missing values and inconsistencies.
- Visualized distributions of variables using histograms and boxplots.
- Examined relationships between features and target variable with scatter plots and correlation heatmaps.
- Encoded categorical variables and scaled features where necessary.

### 2. Data Splitting
- Split data into training (80%) and testing (20%) sets for model validation.

### 3. Model Building
- Developed three different multiple linear regression models using various feature combinations.
- Interpreted regression coefficients to understand feature impacts on price.

### 4. Model Evaluation
- Assessed model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - R-squared (R²)
- Evaluated models on the test set to check generalizability.

### 5. Regularization Techniques
- Applied **Lasso Regression** to perform feature selection and reduce overfitting.
- Applied **Ridge Regression** to penalize large coefficients and mitigate multicollinearity.
- Compared regularized models with standard linear regression.

---

## Tools & Libraries
- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  


*Feel free to reach out for questions or collaboration opportunities!*
