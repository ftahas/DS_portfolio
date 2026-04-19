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

### 9. Financial Market Analysis

> Portfolio optimization, risk management, and Monte Carlo simulation across a multi-asset universe.

Quantitative analysis of 8 assets across 5 sectors over 10+ years (2,737 trading days). Constructs the Markowitz efficient frontier with 8,000 random portfolios, computes VaR/CVaR risk metrics, runs 1,000-path Monte Carlo projections, and overlays bull/bear/high-vol regime detection on performance.

**Best portfolio:** Max Sharpe — SR = 1.56, 10.8% return, 7.0% vol &ensp;|&ensp; **Stack:** SciPy Optimize, NumPy

[`Notebook`](Financial_Market_Analysis.ipynb) &ensp; [`Presentation`](financial_presentation.pdf)

---

### 10. Image Classification with CNN Features

> Transfer learning pipeline with t-SNE visualization and multi-class evaluation.

Demonstrates the full CNN image classification workflow on 8,000 synthetic images across 10 classes. Uses 512-dimensional ResNet-style bottleneck features with PCA reduction, t-SNE visualization, inter-class distance analysis, and 4-classifier comparison.

**Result:** Near-perfect accuracy on CNN embeddings &ensp;|&ensp; **Stack:** PCA, t-SNE, Scikit-learn

[`Notebook`](Image_Classification_CNN.ipynb) &ensp; [`Presentation`](cnn_presentation.pdf)

---

### 11. Survival Analysis in Healthcare

> Kaplan-Meier curves, hazard ratios, and clinical risk stratification.

Time-to-event analysis on 4,000 patients with treatment, staging, and biomarker data. Includes KM curves stratified by treatment/stage/smoking, hazard ratio forest plots, 2-year event prediction, calibration analysis, and model-based risk group stratification.

**Best model:** Logistic Regression — AUC = 0.789 &ensp;|&ensp; **Stack:** Survival Analysis, Scikit-learn

[`Notebook`](Survival_Analysis.ipynb) &ensp; [`Presentation`](survival_presentation.pdf)

---

### 12. Recommendation System

> Collaborative filtering with SVD matrix factorization and personalized top-N generation.

Builds and evaluates recommendation models on 1,500 users, 500 items, and ~75K ratings. Compares global/user/item mean baselines against SVD, includes sparsity analysis, genre preference correlations, singular value spectrum, and personalized recommendation output.

**Best model:** SVD (K=20) outperforms baselines &ensp;|&ensp; **Stack:** SciPy SVD, Pandas

[`Notebook`](Recommendation_System.ipynb) &ensp; [`Presentation`](recsys_presentation.pdf)

---

### 13. MLOps Pipeline

> End-to-end deployment with model versioning, drift detection, A/B testing, and automated retraining.

Production-grade ML pipeline simulating 90 days of model deployment (18,000 predictions). Demonstrates the full MLOps lifecycle: multi-version model registry, real-time accuracy/latency monitoring, drift detection via PSI and calibration analysis, champion/challenger A/B testing, and cost-benefit driven retraining triggers.

**Outcome:** Drift detected at Day 60, retraining yielded **+22% accuracy** &ensp;|&ensp; **Stack:** Scikit-learn, PSI, Drift Detection

[`Notebook`](MLOps_Pipeline.ipynb) &ensp; [`Presentation`](mlops_presentation.pdf)

---

### 14. Reinforcement Learning Trading Agent

> Q-learning agent in a custom Gym-style trading environment, benchmarked against classical strategies.

A tabular Q-learning agent learns to BUY/SELL/HOLD a single asset by interacting with a custom trading environment over 200 training episodes. Trained on 10 years of synthetic price data with bull/bear/sideways regime switching, then benchmarked against Buy & Hold, MA Crossover, and Random strategies.

**Result:** RL achieves +111% test return, Sharpe 1.73, +60 points over Random &ensp;|&ensp; **Stack:** Q-Learning, NumPy, Pandas

[`Notebook`](RL_Trading_Agent.ipynb) &ensp; [`Presentation`](rl_trading_presentation.pdf)

---

### 15. LLM & Agent Evaluation Framework

> Multi-model benchmarking with quality, latency, cost, hallucination, and agent trajectory analysis.

A comprehensive evaluation suite comparing 6 LLMs across 8 task categories (9,600 total evaluations) plus 500 agent trajectories. Includes cost-accuracy Pareto analysis, LLM-as-Judge calibration, pairwise statistical significance testing, and use-case-specific recommendations.

**Result:** Production-ready framework with full leaderboard and Pareto frontier &ensp;|&ensp; **Stack:** Statistical Testing, Pareto Optimization

[`Notebook`](LLM_Evaluation.ipynb) &ensp; [`Presentation`](llm_eval_presentation.pdf)

---

### 16. IoT Anomaly Detection

> Industrial sensor monitoring with statistical, ML, and reconstruction-based methods.

Real-time anomaly detection on 30 days of multi-sensor IoT data from an industrial pump (43,200 timestamps × 5 sensors). Benchmarks 7 methods against 5 distinct anomaly types (spikes, drifts, multivariate failures), with root-cause attribution via PCA reconstruction error.

**Best result:** Z-Score achieves 99.4% precision, F1 = 0.80; PCA AUC-PR = 0.79 &ensp;|&ensp; **Stack:** Isolation Forest, One-Class SVM, PCA

[`Notebook`](IoT_Anomaly_Detection.ipynb) &ensp; [`Presentation`](iot_anomaly_presentation.pdf)

---

### 17. Credit Risk Modeling

> Banking risk pipeline — PD, LGD, EAD, Expected Loss, Basel capital, stress testing, fairness audit.

End-to-end credit risk modeling on a 15,000-loan portfolio ($375M exposure). Implements the full Basel IRB framework: PD models with industry-standard metrics (Gini, KS), credit scorecards (300-850), LGD regression, Expected Loss computation, Risk-Weighted Assets, stress testing across 5 regulatory scenarios, and Disparate Impact fairness audit.

**Result:** Gini=0.52, KS=0.39 (production-grade); EL=$95.9M; passes 4/5 fair lending rule &ensp;|&ensp; **Stack:** Logistic Regression, Basel IRB, Stress Testing

[`Notebook`](Credit_Risk_Modeling.ipynb) &ensp; [`Presentation`](credit_risk_presentation.pdf)

---

### 18. Text Summarization Pipeline

> Extractive & abstractive summarization with custom ROUGE evaluation, compression analysis, and statistical testing.

A comprehensive NLP pipeline evaluating 8 summarization methods (5 extractive + 3 abstractive) on an 800-document corpus across 6 domains. Implements ROUGE-1/2/L from scratch, compression-quality tradeoffs, precision-recall analysis, domain-specific evaluation, and Wilcoxon significance testing.

**Result:** Pegasus achieves ROUGE-1=0.69, outperforming best extractive (TF-IDF, 0.41) by +28pp &ensp;|&ensp; **Stack:** ROUGE, TF-IDF, TextRank, LSA

[`Notebook`](Text_Summarization.ipynb) &ensp; [`Presentation`](summarization_presentation.pdf)

---

### 19. Object Detection Pipeline

> Multi-model CV benchmark with custom mAP, error taxonomy, speed-accuracy Pareto, and size-stratified analysis.

Evaluates 5 detection architectures (YOLOv8-L/S, Faster R-CNN, SSD-300, EfficientDet-D2) on a 2,000-image dataset with 8 object classes. Implements mAP@50 and mAP@[.5:.95] from scratch, per-class precision-recall curves, IoU distributions, error taxonomy (classification/localization/background), and confidence threshold tuning.

**Result:** Faster R-CNN leads (mAP@50=0.70); EfficientDet best efficiency (8.1M params) &ensp;|&ensp; **Stack:** mAP, IoU, Object Detection

[`Notebook`](Object_Detection.ipynb) &ensp; [`Presentation`](detection_presentation.pdf)

---

### 20. Bayesian Optimization for Hyperparameter Tuning

> GP surrogate, acquisition functions (EI/UCB/PI), practical HPO benchmark vs Grid/Random search.

Implements Bayesian Optimization from scratch with Gaussian Process surrogates and three acquisition functions. Demonstrates on 1D/2D synthetic benchmarks (Branin) and practical 5D hyperparameter tuning of GradientBoosting. Includes convergence analysis, cumulative regret, exploration-exploitation tradeoff, and GP uncertainty reduction visualization.

**Result:** BO finds best config with lowest cumulative regret; outperforms Grid/Random &ensp;|&ensp; **Stack:** Gaussian Processes, Acquisition Functions

[`Notebook`](Bayesian_Optimization.ipynb) &ensp; [`Presentation`](bo_presentation.pdf)

---

### 21. Deep Recommender System

> Neural Collaborative Filtering (NeuMF) from scratch, SVD baseline, ranking metrics, cold start analysis.

Implements NeuMF (GMF + MLP paths) from scratch in NumPy. Benchmarked against SVD, popularity, and content-based on 80K interactions with comprehensive ranking evaluation (NDCG, HR, MAP), embedding visualization, cold start analysis, and A/B test simulation.

**Result:** SVD leads (NDCG@10=0.035); NCF learns meaningful embeddings &ensp;|&ensp; **Stack:** Neural Networks, SVD, Ranking Metrics

[`Notebook`](Deep_RecSys.ipynb) &ensp; [`Presentation`](deep_recsys_presentation.pdf)

---

### 22. Time Series Financial Fraud Detection

> Sequential transaction analysis with temporal features, CUSUM change points, and alert fatigue analysis.

Focuses on temporal fraud patterns (burst attacks, escalation, impossible travel, night attacks) rather than static features. Engineers per-customer behavioral features and detects spending regime shifts. Includes CUSUM change point detection and operational alert fatigue analysis.

**Result:** AUC=0.999 with temporal features; 68.5% precision at 80% recall &ensp;|&ensp; **Stack:** Time Series, CUSUM, Isolation Forest

[`Notebook`](TimeSeries_Fraud.ipynb) &ensp; [`Presentation`](ts_fraud_presentation.pdf)

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
| 9 | Financial Market Analysis | Quant Finance | Sharpe Ratio | 1.56 |
| 10 | Image Classification (CNN) | Deep Learning | Accuracy | ~1.00 |
| 11 | Survival Analysis | Healthcare | AUC (2-yr) | 0.789 |
| 12 | Recommendation System | RecSys | RMSE (SVD) | Beats baselines |
| 13 | MLOps Pipeline | Production ML | Retrain Improvement | +22% accuracy |
| 14 | RL Trading Agent | Reinforcement Learning | Sharpe Ratio | 1.73 |
| 15 | LLM Evaluation Framework | LLM Ops | Top Model Accuracy | 88.8% |
| 16 | IoT Anomaly Detection | Industrial ML | F1-Score | 0.80 |
| 17 | Credit Risk Modeling | Banking Risk | Gini / KS | 0.52 / 0.39 |
| 18 | Text Summarization | NLP / NLG | ROUGE-1 (Pegasus) | 0.691 |
| 19 | Object Detection | Computer Vision | mAP@50 (F-RCNN) | 0.698 |
| 20 | Bayesian Optimization | Meta-ML / HPO | Best AUC (BO) | 0.978 |
| 21 | Deep Recommender System | Deep Learning RecSys | NDCG@10 (SVD) | 0.035 |
| 22 | TS Fraud Detection | Financial Crime | F1 (GB Temporal) | 0.993 |
| 22 | TS Financial Fraud | Time Series Fraud | AUC-ROC | 0.999 |
