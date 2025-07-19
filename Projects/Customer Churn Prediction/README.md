
# 📊 Customer Churn Prediction using Logistic Regression

This project predicts whether a customer will churn (leave) using a cleaned telecom dataset. The solution involves **data preprocessing**, **exploratory analysis**, **feature selection**, and a **Logistic Regression model**, evaluated with various metrics. SHAP is used for interpreting feature importance.

---

## 🚀 Project Highlights

* Cleaned and transformed telecom customer data.
* Performed EDA and statistical analysis to find trends and patterns.
* Used **Logistic Regression** to predict churn with good accuracy.
* Applied **SHAP (SHapley Additive exPlanations)** to identify key churn indicators.
* Retrained model using top features for improved interpretability.

---

## 🧰 Tools & Technologies

* Python, pandas, NumPy
* Matplotlib, seaborn
* Scikit-learn (Logistic Regression, metrics)
* SHAP
* Jupyter Notebook

---

## 🔎 Workflow

1. **Data Cleaning**

   * Handled missing values
   * Converted data types (e.g., `TotalCharges` from string to float)
   * Encoded categorical features

2. **EDA (Exploratory Data Analysis)**

   * Visualized trends using bar plots, line charts, and correlation heatmaps
   * Identified churn behavior among demographics, services, and payment methods

3. **Statistical Analysis**

   * Applied Chi-Square tests to determine significance of categorical variables

4. **Model Building**

   * Split dataset into training and testing sets
   * Trained and evaluated Logistic Regression with accuracy, confusion matrix, ROC

5. **Feature Selection using SHAP**

   * Identified most important features affecting churn
   * Retrained the model using top 5 features to improve generalization

---

## 📈 Results

* Model showed balanced accuracy with business interpretability
* SHAP summary revealed that contract type, monthly charges, and tenure were key indicators of churn

---

## 📁 Dataset

The dataset used was a sample telecom dataset with \~3,700 customer records. You can download it from [Kaggle Telecom Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) or use the version included in this repo.

---

## 🤝 Contributions

This project was completed as part of a Data Analyst Internship. Contributions welcome for enhancements and model improvements.


