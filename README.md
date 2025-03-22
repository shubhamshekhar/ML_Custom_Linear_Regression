# Custom Linear Regression from Scratch

## 📌 Project Overview
This project implements **Linear Regression** from scratch using Python and NumPy, without relying on libraries like `scikit-learn`. The objective is to gain an in-depth understanding of how linear regression works by implementing it manually.

## 🔍 What is Linear Regression?
Linear Regression is a supervised learning algorithm used for predicting a continuous dependent variable (Y) based on independent variable(s) (X). The hypothesis function is:

\[
Y = W X + b
\]

where:
- **W**: Weight (slope)
- **b**: Bias (intercept)
- **X**: Feature/input
- **Y**: Predicted output

The model is trained using the **Gradient Descent** optimization algorithm to minimize the Mean Squared Error (MSE):

\[
MSE = \frac{1}{n} \sum (Y_{actual} - Y_{predicted})^2
\]

## 🔧 Technologies Used
- **Python**
- **NumPy**
- **Matplotlib & Seaborn** (for visualization)
- **Pandas** (for dataset handling)

## 📜 Features Implemented
- Data preprocessing (handling missing values, normalization)
- Custom implementation of:
  - Cost function (Mean Squared Error)
  - Gradient Descent algorithm
  - Model training and evaluation
- Comparison with `sklearn` Linear Regression for validation
- Visualizations for error reduction over iterations

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/shubhamshekhar/ML_Custom_Linear_Regression.git
   ```
2. Navigate to the project directory:
   ```bash
   cd custom-linear-regression
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Python script:
   ```bash
   python linear_regression.py
   ```

## 📊 Expected Results
- A trained linear regression model with optimized weights.
- Loss function visualization showing error reduction.
- Comparison with `scikit-learn` implementation.

## 📄 License
This project is licensed under the **MIT License**.

---
**💡 Contributions & Issues:** Feel free to open a pull request or issue if you'd like to contribute! 🚀

