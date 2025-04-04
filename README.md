# NYC School Closure Predictor

A data science project that analyzes student outcomes across New York City high schools to explore the relationship between performance metrics and school closures. This project focuses on subgroup disparities and predictive modeling.

## 📚 Project Overview

Using publicly available datasets from the New York State Education Department and the City of New York, this project investigates:

- How graduation rates, dropout rates, and GED completions vary by demographic groups
- Which student metrics are most correlated with school closures
- Whether we can build a predictive model for identifying at-risk schools

## 🧠 Key Findings

- Black and African American students, as well as male students, consistently had higher dropout rates.
- Dropout rates were the strongest predictors of school closures among the features tested.
- A logistic regression model trained on 2015 data achieved **99.1% accuracy** in cross-validation.

## 📊 Tools & Techniques

- Python, Pandas, NumPy, Scikit-learn
- Logistic Regression for classification
- Data cleaning, merging, and feature engineering
- Cross-validation (5-fold)
- Exploratory data analysis & subgroup comparisons

## 🔗 Live Project Page

[View Project](https://ethanperello.github.io/New-York-Student-Outcomes-and-School-Closures/)

## 🤝 Collaborators

This project was completed in collaboration with **Adam Goodman**.

### My primary contributions:
- Conducted subgroup analysis across race and gender
- Engineered features for predictive modeling
- Trained and evaluated the logistic regression model

## 🧠 What I Learned

- How subgroup performance data can signal system-wide issues
- The power of simple models (like logistic regression) when paired with clean, insightful features
- How to extract insight from large datasets and translate it into actionable outcomes
