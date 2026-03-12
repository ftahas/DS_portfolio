# 🔮 Customer Churn Prediction — End-to-End ML Pipeline

## Overview
A complete machine learning project predicting customer churn for a telecom company with 7,500 customers. Includes EDA, statistical testing, model comparison, and business impact analysis.

## Project Structure
```
01-customer-churn-prediction/
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb    # Full analysis notebook
├── presentation/
│   ├── churn_presentation.tex             # LaTeX source
│   └── churn_presentation.pdf             # Compiled presentation (18 slides)
├── figures/                               # 12 publication-quality visualizations
│   ├── 01_churn_distribution.png
│   ├── 02_churn_by_contract.png
│   ├── ...
│   └── 12_learning_curve.png
├── data/
│   └── telecom_churn.csv                  # Dataset (7,500 × 18)
└── README.md
```

## Key Results
| Model | Accuracy | F1-Score | AUC-ROC |
|:------|:---------|:---------|:--------|
| Logistic Regression | 0.653 | 0.562 | **0.716** |
| Random Forest | 0.656 | 0.561 | 0.704 |
| Gradient Boosting | 0.646 | 0.559 | 0.690 |

## Tech Stack
`Python` `Scikit-learn` `Pandas` `Matplotlib` `Seaborn` `SciPy` `LaTeX Beamer`

## Highlights
- 5 statistical hypothesis tests with effect sizes
- 3 models compared with cross-validation
- Business impact analysis with ROI projections
- 18-slide LaTeX Beamer presentation with embedded figures
