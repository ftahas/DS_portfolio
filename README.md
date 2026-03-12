<div align="center">

# Data Science Portfolio

**Felipe Taha Sant'Ana**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ftsantana)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ftahas)
[![Email](https://img.shields.io/badge/Email-8B5CF6?style=flat-square&logo=protonmail&logoColor=white)](mailto:ftahas@proton.me)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0003-0802-9919)

A collection of end-to-end data science projects spanning classification, regression, NLP, time series, clustering, and experimentation. Each project includes a full Jupyter notebook with analysis and a LaTeX Beamer presentation summarizing key findings.

</div>

---

## Projects

### 1. Customer Churn Prediction

> End-to-end ML pipeline for proactive telecom customer retention.

Predicts which customers are likely to churn using 7,500 telecom records with 18 features. Includes 5 statistical hypothesis tests, 3 model comparisons, and a business impact analysis projecting $3.2M+ in annual retention savings.

**Best model:** Logistic Regression — AUC-ROC = 0.716 &ensp;|&ensp; **Stack:** Scikit-learn, SciPy, Pandas

[`Notebook`](Customer_Churn_Prediction.ipynb) &ensp; [`Presentation`](churn_presentation.pdf)

---

### 2. Real Estate Price Forecasting

> Regression modeling for automated property valuation and investment analysis.

Forecasts real estate prices across 8 neighborhoods using 8,000 transactions with property, location, and temporal features. Features neighborhood appreciation analysis (CAGR), investment heatmaps, and residual diagnostics.

**Best model:** Gradient Boosting — R² = 0.913, MAPE = 10.8% &ensp;|&ensp; **Stack:** Scikit-learn, GeoPandas concepts

[`Notebook`](Real_Estate_Forecasting.ipynb) &ensp; [`Presentation`](realestate_presentation.pdf)

---

### 3. NLP Sentiment Analysis

> Multi-class text classification on product reviews using TF-IDF and ensemble methods.

Classifies 6,000 product reviews (6 categories) into Positive, Neutral, and Negative sentiment. Uses TF-IDF with bigrams and compares 4 classifiers. Includes per-class coefficient analysis for model interpretability.

**Best model:** Linear SVC — Accuracy = 99.7%, F1-Macro = 0.996 &ensp;|&ensp; **Stack:** Scikit-learn, NLP, TF-IDF

[`Notebook`](NLP_Sentiment_Analysis.ipynb) &ensp; [`Presentation`](nlp_presentation.pdf)

---

### 4. Energy Consumption Forecasting

> Hourly demand prediction using lag features, cyclical encodings, and weather data.

Forecasts hourly energy consumption using 3 years of data (26,304 observations). Captures daily load profiles, weekday/weekend patterns, and a U-shaped temperature-demand relationship through cyclical sin/cos encodings and 1h/24h/168h lag features.

**Best model:** Gradient Boosting — R² = 0.809, MAPE = 4.66% &ensp;|&ensp; **Stack:** Scikit-learn, Time Series

[`Notebook`](Energy_Forecasting.ipynb) &ensp; [`Presentation`](energy_presentation.pdf)

---

### 5. Customer Segmentation

> Unsupervised clustering with RFM analysis for actionable marketing segments.

Segments 5,000 e-commerce customers using K-Means on RFM and behavioral features. Includes elbow/silhouette optimization, PCA visualization, radar chart profiles, and segment-specific marketing strategies.

**Result:** 5 distinct segments — Silhouette = 0.30 &ensp;|&ensp; **Stack:** Scikit-learn, K-Means, PCA

[`Notebook`](Customer_Segmentation.ipynb) &ensp; [`Presentation`](clustering_presentation.pdf)

---

### 6. Credit Card Fraud Detection

> Imbalanced classification with precision-recall optimization and threshold tuning.

Detects fraudulent transactions in a dataset of 10,000 records with only 3% fraud rate. Addresses class imbalance through weighted models and evaluates with AUC-PR as the primary metric. Includes PCA projection and threshold optimization curves.

**Best model:** Gradient Boosting — AUC-PR = 0.941, F1 = 0.867 &ensp;|&ensp; **Stack:** Scikit-learn, Imbalanced Learning

[`Notebook`](Fraud_Detection.ipynb) &ensp; [`Presentation`](fraud_presentation.pdf)

---

### 7. Supply Chain Demand Forecasting

> Multi-product, multi-warehouse prediction with inventory optimization.

Forecasts weekly demand across 5 products and 3 warehouses over 5 years (3,915 records). Includes promotional lift analysis, seasonal decomposition, and a safety stock optimization framework balancing stockout rates against holding costs.

**Best model:** Random Forest — R² = 0.959, MAPE = 7.1% &ensp;|&ensp; **Stack:** Scikit-learn, Inventory Optimization

[`Notebook`](Supply_Chain_Forecasting.ipynb) &ensp; [`Presentation`](supply_chain_presentation.pdf)

---

### 8. A/B Testing & Experimentation

> Statistical experimentation framework combining frequentist and Bayesian methods.

Analyzes 3 experiments (29,000 total observations) covering conversion rates, revenue, and engagement. Demonstrates chi-squared tests, Bayesian beta posteriors, bootstrap confidence intervals, power analysis, sequential monitoring, and Benjamini-Hochberg multiple testing correction.

**Highlights:** Bayesian lift estimation, power curves, O'Brien-Fleming boundaries &ensp;|&ensp; **Stack:** SciPy, Bayesian Statistics

[`Notebook`](AB_Testing_Framework.ipynb) &ensp; [`Presentation`](ab_testing_presentation.pdf)

---

## Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=flat-square&logo=python&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</div>

---

## Summary

| # | Project | Domain | Key Metric | Best Result |
|:-:|:--------|:-------|:-----------|:------------|
| 1 | Customer Churn Prediction | Classification | AUC-ROC | 0.716 |
| 2 | Real Estate Forecasting | Regression | R² / MAPE | 0.913 / 10.8% |
| 3 | NLP Sentiment Analysis | NLP | F1-Macro | 0.996 |
| 4 | Energy Forecasting | Time Series | MAPE | 4.66% |
| 5 | Customer Segmentation | Clustering | Silhouette | 0.30 |
| 6 | Fraud Detection | Imbalanced Classif. | AUC-PR | 0.941 |
| 7 | Supply Chain Forecasting | Multi-Product TS | R² / MAPE | 0.959 / 7.1% |
| 8 | A/B Testing Framework | Experimentation | — | Freq. + Bayesian |
