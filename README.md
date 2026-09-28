# Practical Statistics for Data Scientists - Code Reproduction & Notes

This repository contains the reproduction of code examples, theoretical explanations, and chapter summaries from the book **"Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python" (2nd Edition)** by Peter Bruce, Andrew Bruce, and Peter Gedeck (O'Reilly).

## Table of Contents & Chapter Overview

### Chapter 1: Exploratory Data Analysis (EDA)
Explores fundamental techniques to summarize and visualize structured data:
- Estimates of Location: Mean, trimmed mean, weighted mean, and median.
- Estimates of Variability: Standard deviation, variance, mean absolute deviation (MAD), and interquartile range (IQR).
- Distribution Exploration: Histograms, percentiles, boxplots, and kernel density estimation (KDE).
- Bivariate & Multivariate Analysis: Scatterplots, hexagonal binning, contingency tables, and violin plots.

### Chapter 2: Data and Sampling Distributions
Focuses on understanding population vs. sample properties and mitigating bias:
- Random sampling principles, selection bias, and regression to the mean.
- Sampling distributions, Central Limit Theorem (CLT), and Standard Error.
- The Bootstrap: Resampling with replacement to estimate standard error and build confidence intervals.
- Key probability distributions: Normal (Gaussian), Student's t, Binomial, Chi-Square, F, Poisson, Exponential, and Weibull distributions.

### Chapter 3: Statistical Experiments and Significance Testing
Discusses hypothesis testing and experimental design in a data science context:
- A/B Testing: Treatment vs. control groups and randomization.
- Hypothesis Testing: Null vs. alternative hypotheses, one-way vs. two-way tests.
- Resampling methods: Shuffling and permutation tests.
- Statistical significance, p-values, alpha levels, and Type 1 / Type 2 errors.
- ANOVA (Analysis of Variance) and Chi-Square tests for comparing multiple groups.
- Multi-Arm Bandit algorithms for dynamic optimization.

### Chapter 4: Regression and Prediction
Covers linear models to quantify relationships and predict numeric outcomes:
- Simple linear regression and the Ordinary Least Squares (OLS) method.
- Multiple linear regression, fitted values, and residuals.
- Evaluation metrics: Root Mean Squared Error (RMSE), Residual Standard Error (RSE), and R-squared (R²).
- Model selection: Occam's razor, AIC, BIC, stepwise regression (forward/backward), and cross-validation.
- Categorical variables handling: Reference coding (dummy variables) vs. one-hot encoding.
- Regression diagnostics: Identifying outliers, influential points, and heteroskedasticity.

### Chapter 5: Classification
Addresses supervised learning models for predicting discrete categorical targets:
- Naive Bayes: Conditional probability and Bayes' Theorem.
- Discriminant Analysis (LDA) and covariance matrices.
- Logistic Regression: Logit link function, odds ratios, and maximum likelihood estimation.
- Classification evaluation metrics: Confusion Matrix, Precision, Recall, Specificity, F1-Score, ROC curve, and AUC.
- Strategies for imbalanced classes: Undersampling, oversampling, cost-based classification, and SMOTE.

### Chapter 6: Statistical Machine Learning
Details core modern predictive algorithms:
- K-Nearest Neighbors (KNN): Distance metrics, feature scaling/standardization, and choosing K.
- Decision Trees (CART): Recursive partitioning, measuring impurity (Gini impurity / entropy), and tree pruning.
- Ensemble Methods:
  - Bagging and Random Forests: Variable importance and hyperparameter tuning.
  - Boosting: AdaBoost and XGBoost (Gradient Boosting), regularization, and avoidance of overfitting.

### Chapter 7: Unsupervised Learning
Extracts insights and patterns from unlabeled data:
- Principal Component Analysis (PCA): Dimensionality reduction, loadings, and variance explained.
- K-Means Clustering: Cluster centers, inertia, and determining the optimal number of clusters (elbow method).
- Hierarchical Clustering: Agglomerative clustering, dissimilarity metrics, and dendrogram visualization.
- Model-Based Clustering (Gaussian Mixture Models).
- Scaling numeric variables and dealing with mixed/categorical data (Gower's distance).

## Environment Setup
Clone this repository and install dependencies:
```bash
git clone [https://github.com/] https://github.com/imaaa2805/Practical-Statistics-for-Data-Scientists.git
cd Practical-Statistics-for-Data-Scientists
pip install -r requirements.txt
