# 📈 Simple Linear Regression Analysis on Stock Prices

## 📌 Project Overview

This project demonstrates the implementation of **Simple Linear Regression** using Python and Scikit-learn to predict **stock closing prices** based on **opening prices**. The project includes data preprocessing, model training, evaluation, visualization, and interpretation of results.

This project was completed as part of the **CodeVeda Technologies Internship – Level 2 (Intermediate), Task 1: Regression Analysis**.

---

## 🎯 Objectives

- Load and inspect the Stock Prices dataset.
- Handle missing values in the selected variables.
- Split the dataset into training and testing sets.
- Train a Simple Linear Regression model using Scikit-learn.
- Predict stock closing prices based on opening prices.
- Evaluate the model using R² Score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- Visualize the regression results.

---

## 📂 Dataset

**Dataset Name:** Stock Prices Dataset

The dataset contains historical stock market data with the following attributes:

- Symbol
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume

For this project:

- **Independent Variable (X):** Open Price (`open`)
- **Dependent Variable (y):** Close Price (`close`)

Rows containing missing values in the selected variables were removed before model training.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Model Workflow

1. Import required libraries
2. Load the dataset
3. Inspect the dataset
4. Handle missing values
5. Select predictor and target variables
6. Split the dataset into training and testing sets
7. Train the Simple Linear Regression model
8. Predict closing prices
9. Evaluate model performance
10. Visualize the regression results

---

## 📈 Model Evaluation

The model was evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

### Results

| Metric | Value |
|---------|-------|
| Mean Squared Error (MSE) | 2.7261 |
| Root Mean Squared Error (RMSE) | 1.6511 |
| R² Score | 0.9997 |

The high R² score indicates that the model explains approximately **99.97%** of the variation in the closing stock price, demonstrating excellent predictive performance.

---

## 📉 Regression Equation

**Closing Price = 0.0267 + (0.9999 × Opening Price)**

The regression coefficient indicates a strong positive linear relationship between the opening and closing prices, showing that the opening price is an excellent predictor of the closing price.

---

## 📷 Visualizations

The project includes the following visualizations:

- Dataset Preview
- Missing Values Summary
- Regression Line Plot
- Actual vs Predicted Values Plot

---

## 📌 Key Findings

- The opening price is a strong predictor of the closing price.
- The regression model achieved an excellent fit with an R² score of **0.9997**.
- Prediction errors were minimal, as indicated by the low MSE and RMSE values.
- The regression line and prediction plots confirmed a strong positive linear relationship between the opening and closing prices.
- The model provides highly accurate predictions for stock closing prices.

---

## ✅ Conclusion

A Simple Linear Regression model was successfully developed to predict stock closing prices using opening prices. After preprocessing the data and removing missing values, the model achieved excellent predictive performance with a very high R² score and low prediction errors. The results demonstrate that Simple Linear Regression is an effective technique for modeling the relationship between stock opening and closing prices.

---

## 📁 Project Structure

```
Regression-Analysis-Stock-Prices/
│
├── Regression_Analysis.ipynb
├── Regression_Report.pdf
├── stock_price_predictions.csv
├── 2) Stock Prices Data Set(1).csv
├── README.md
└── images/
    ├── regression_line_plot.png
    ├── actual_vs_predicted.png
```

---

## 🚀 How to Run


1. Navigate to the project directory.

```bash
cd Regression-Analysis-Stock-Prices
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells in `Regression_Analysis.ipynb`.

---

## 🔗 Dataset Source

The Stock Prices Dataset used in this project was provided as part of the internship task. If you are using a publicly available version, include the appropriate dataset source or download link here.

---

## 👤 Author

**Vihangi Hewanayake**

CodeVeda Technologies Internship – Level 2 (Intermediate)

---