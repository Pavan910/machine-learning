# Machine Learning Projects

A collection of end-to-end machine learning projects built with Python, covering regression, classification, and model evaluation techniques aligned with industry and academic standards.

---

## Projects

### 1. House Price Prediction
**File:** `house price prediction-checkpoint.ipynb`

Predicts residential property prices using supervised learning regression techniques.

**Problem:** Given features like area, number of bedrooms, location type, and amenities, predict the sale price of a house.

**Approach:**
- Exploratory Data Analysis (EDA) with correlation heatmaps and distribution plots
- Feature engineering: handling missing values, encoding categorical variables, outlier removal
- Models compared: Linear Regression, Ridge Regression, Lasso Regression
- Evaluation metrics: RMSE, MAE, R² score

**Key results:**
- Ridge Regression achieved best R² of ~0.85 on test set
- Identified top 5 features driving price: area, location, age of property, number of bathrooms, floor

---

### 2. Linear Regression — From Scratch
**File:** `Linear_Regression_Model.ipynb`

A ground-up implementation of linear regression without using scikit-learn's `LinearRegression`, demonstrating mathematical understanding of the algorithm.

**What's covered:**
- Ordinary Least Squares (OLS) derivation
- Gradient descent implementation with configurable learning rate and epochs
- Cost function (MSE) visualization across iterations
- Comparison with scikit-learn's implementation to validate correctness
- Statistical output: coefficients, p-values, confidence intervals

**Why this matters:** Understanding regression at the mathematical level is a prerequisite for statistical inference — the foundation of programs like LMU's Statistics & Data Science MSc.

---

## Setup

```bash
git clone https://github.com/Pavan910/machine-learning.git
cd machine-learning
pip install -r requirements.txt
jupyter notebook
```

**Dependencies:**
```
numpy
pandas
matplotlib
seaborn
scikit-learn
jupyter
```

---

## Skills Demonstrated

`Regression Analysis` `Feature Engineering` `Model Evaluation` `Statistical Inference` `Python` `NumPy` `pandas` `scikit-learn` `matplotlib`

---

## Author

**Pavan Singh** — AI/ML Engineer
[LinkedIn](https://www.linkedin.com/in/pavan-singh-b16652190/) · [Portfolio](https://pavan-singh-portfolio.vercel.app/)
