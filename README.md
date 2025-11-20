# Salary-Prediction-Project
## Comprehensive Analysis: Regression and Classification of Salary Data
Bivariate, Multivariate, and Regression analysis on salary data

# Salary Prediction

## Project Overview
This project performs a dual analysis on employee salary data:
1.  **Regression:** Predicting the **continuous dollar value** of an employee's salary.
2.  **Classification:** Predicting the **binary likelihood** of an employee earning a **six-figure salary (>$100,000)**.

## Key Findings: Regression
* **Experience Impact:** For every year of work, salary increases by approximately **$5,759**.
* **The PhD Premium:** Holding a PhD adds **$21,449** to an annual salary compared to a Bachelor's degree.
* **The Master's Boost:** A Master's degree adds **$11,388** over a Bachelor's.
* **High School Penalty:** Stopping education at High School results in a **$37,546** salary deficit compared to a Bachelor's.
* **Model Accuracy:** The final model achieved an **R² score of 0.71**.

## Feature Importance
The following chart visualises the estimated dollar impact of each feature on annual salary:

![Feature Importance Chart](Featureimportance.png)

---
## Key Findings: Classification
The Logistic Regression model was trained to predict the odds of an employee earning $>\$100,000$ (six figures).
* **ROC AUC Score: $\mathbf{0.9389}$** — This demonstrates excellent predictive power, showing the model has a $93.89\%$ chance of correctly distinguishing between a six-figure earner and a non-six-figure earner.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r Requirements.txt`
3. Choose your analysis track:
    * **Regression Analysis:** Open `Salary_prediction_LinearRegression.ipynb`
    * **Classification Analysis:** Open `Salary_Prediction_LogisticRegression.ipynb`
