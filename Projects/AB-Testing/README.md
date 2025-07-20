
# 🧪 A/B Testing: Landing Page Conversion Rate Analysis

This project analyzes an A/B test conducted on a website's landing pages to determine whether the **new landing page** (treatment group) leads to a higher user conversion rate compared to the **old landing page** (control group).

---

## 📌 Objective

To evaluate whether the new landing page improves the user conversion rate using statistical testing (Chi-Square test) and data analysis.

---


## 🔧 Tools & Libraries

- Python
- Pandas
- Matplotlib & Seaborn
- Scipy.stats (Chi-Square Test)
- Jupyter Notebook

---

## 🔍 Steps Performed

1. **Data Cleaning**
   - Checked for duplicates, mismatches between group and landing page.
   - Verified group/page integrity (control with old, treatment with new).

2. **Exploratory Data Analysis (EDA)**
   - Visualized group-wise conversion rate using bar plots.
   - Summarized user behavior and conversion statistics.

3. **Statistical Testing**
   - Performed Chi-Square test to check if conversion differences are significant.

---

## 📊 Results

| Group     | Conversions | Total Users | Conversion Rate |
|-----------|-------------|-------------|------------------|
| Control   | 273         | 2504        | 10.90%           |
| Treatment | 348         | 2496        | 13.94%           |

- **Chi-Square Statistic**: `10.34`  
- **p-value**: `0.0013`

✅ **Conclusion**: The difference in conversion rates is statistically significant. The new landing page is more effective.

---

## ✅ Conclusion

This analysis supports implementing the new landing page to improve business performance. The insights were derived using real A/B testing principles with proper statistical validation.

---

## 📁 Project Files

- `ab_test_data_5000.csv`: Dataset
- `ab_test_analysis.ipynb`: Full Jupyter notebook with code, plots, and analysis
- `README.md`: Project summary

