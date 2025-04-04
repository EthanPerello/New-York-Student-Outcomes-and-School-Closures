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
- Interactive data visualizations (optional: add screenshots if you have them)

## 🗂️ File Structure

- `data/`: Raw and cleaned datasets
- `notebooks/`: Jupyter notebooks for exploration, modeling, and visualization
- `predict_closure.py`: Script for training and testing the model
- `charts/`: (Optional) Visualizations showing dropout rates, closure trends, etc.

## 🔗 Live Website

[View Project Page](https://ethanperello.github.io/New-York-Student-Outcomes-and-School-Closures/)

## 📁 GitHub Repository

[NYC School Closure Repo](https://github.com/EthanPerello/New-York-Student-Outcomes-and-School-Closures)

## 🧠 What I Learned

- How to use data science techniques to analyze real-world policy-related data
- How subgroup analysis can reveal hidden patterns in education outcomes
- How to train and validate a logistic regression model for real-world classification
