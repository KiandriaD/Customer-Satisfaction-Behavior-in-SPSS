# 📊 Customer Satisfaction Analysis (SPSS)
## 🧾 Project Overview

This project uses SPSS to analyze customer satisfaction data and evaluate how demographics, support interactions, and customer segmentation relate to satisfaction scores. The analysis applies inferential statistics to answer business-focused research questions. This dataset came from [Kaggle.com](https://www.kaggle.com/datasets/salahuddinahmedshuvo/customer-satisfaction-scores-and-behavior-data).

## ❓ Research Questions

1. Is customer location related to whether support was contacted?

2. Can satisfaction score be predicted by age, loyalty level, and support contact?

3. Does satisfaction score differ between Customer Group A and Group B?

## 🛠️ Tools Used

SPSS – Statistical analysis

Excel – Data cleaning and transformation

## 🧹 Data Preparation

Reduced location data from city-level to state-level (LocationSTATE) for categorical analysis.

Converted categorical variables (loyalty level and support contact) into numeric values using Automatic Recode in SPSS.

Reviewed data types to ensure compatibility with statistical tests.

# 🧪 Statistical Analyses & Results
## 📊 Is location related to whether customers contacted support?

Test Used: *Chi-Square Test of Independence*

Result: p = 0.582

Conclusion: No statistically significant relationship between location and contacting support.

## 📐 Predicting Satisfaction Score

Test Used: *Multiple Linear Regression*

Predictors: Age, Loyalty Level, Support Contact

Result: F(3,116) = 0.983, p = 0.403, R² ≈ 0.025

Conclusion: The differences are too small to be meaningful so they are basically statistically insignificant.
## 🅰️🅱️ Satisfaction by Customer Group

Test Used: *Independent Samples t-Test*

Result: t(118) = −0.664, p = 0.508

Conclusion: No significant difference in satisfaction scores between Group A and Group B.

## 📌 Key Takeaways

Customer location does not influence support contact behavior.

Satisfaction scores could not be reliably predicted by age, loyalty, or support contact.

No meaningful satisfaction differences exist between customer groups.

## 🛠️ Skills Demonstrated
Statistical Methods: 
* Regression Analysis 
* Chi-Square, T-Tests 
* Hypothesis Testing

## ✨ Author
Kiandria Davis

## 📌 Portfolio Note
This project is part of my data analytics portfolio and I want to showcase my statistic analysis abilities. 
