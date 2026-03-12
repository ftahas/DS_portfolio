# 🏠 Real Estate Price Forecasting — Regression & Market Analysis

## Overview
A comprehensive regression project forecasting real estate prices across 8 neighborhoods using 8,000 transactions. Includes geospatial analysis, temporal trends, and investment strategy recommendations.

## Project Structure
```
02-real-estate-forecasting/
├── notebooks/
│   └── Real_Estate_Forecasting.ipynb      # Full analysis notebook
├── presentation/
│   ├── realestate_presentation.tex        # LaTeX source
│   └── realestate_presentation.pdf        # Compiled presentation (17 slides)
├── figures/                               # 12 publication-quality visualizations
│   ├── 01_price_distribution.png
│   ├── 02_price_by_neighborhood.png
│   ├── ...
│   └── 12_investment_heatmap.png
├── data/
│   └── real_estate.csv                    # Dataset (8,000 × 20)
└── README.md
```

## Key Results
| Model | R² | RMSE | MAPE |
|:------|:---|:-----|:-----|
| Linear Regression | 0.744 | $88,558 | 19.5% |
| Ridge Regression | 0.744 | $88,556 | 19.5% |
| Lasso Regression | 0.744 | $88,508 | 19.5% |
| Random Forest | 0.878 | $66,460 | 12.9% |
| **Gradient Boosting** | **0.913** | **$54,724** | **10.8%** |

## Tech Stack
`Python` `Scikit-learn` `Pandas` `Matplotlib` `Seaborn` `SciPy` `LaTeX Beamer`

## Highlights
- 5 statistical tests (ANOVA, Pearson, Spearman, Welch's t, Kruskal-Wallis)
- 5 regression models compared with cross-validation
- Neighborhood-level appreciation analysis with CAGR
- Investment strategy matrix with risk assessment
- 17-slide LaTeX Beamer presentation with embedded figures
