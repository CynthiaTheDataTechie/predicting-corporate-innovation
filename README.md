# predicting-corporate-innovation
A comparative study of logistic regression and random forest models to predict corporate innovation
# Predicting Corporate Innovation

A comparative study of logistic regression and random forest models to predict corporate innovation, providing insights into which model performs better under specific conditions.

---

## Overview

This project explores predicting corporate innovation using two machine learning models:
- **Logistic Regression**: A simple, interpretable model.
- **Random Forest**: A robust, ensemble-based approach for handling complex datasets.

---

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Methodology](#methodology)
- [Results](#results)
- [How to Use](#how-to-use)
- [Folder Structure](#folder-structure)
- [Blog Post](#blog-post)
- [Video Walkthrough](#video-walkthrough)
- [License](#license)

---

## Features
- Implementation of logistic regression and random forest models.
- Model evaluation using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
- Visualizations for model performance and feature importance.

---

## Methodology
1. **Data Preprocessing**:
   - Cleaned and handled missing values (details in the notebook).
   - Features were scaled for consistency.
2. **Model Implementation**:
   - Logistic Regression: A linear model for binary classification.
   - Random Forest: An ensemble method for improved accuracy.
3. **Model Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC.
   - Visualizations: ROC Curves, Precision-Recall Curves, Feature Importances.

---

## Results
- **Logistic Regression**:
  - High interpretability and decent performance on smaller datasets.
- **Random Forest**:
  - Superior accuracy and robustness for complex datasets.

Key visualizations include:
- ROC-AUC curves for model comparison.
- Feature importance from the Random Forest model.

---

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/predicting-corporate-innovation.git
   cd predicting-corporate-innovation
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
predicting-corporate-innovation/
├── notebooks/                # Jupyter notebooks for the project
│   ├── analysis.ipynb         # Main notebook for the project
├── results/                  # Analysis outputs
│   ├── figures/               # Saved plots (e.g., ROC curves, feature importance)
│   ├── README.md              # Documentation for results
├── requirements.txt          # Python dependencies
├── LICENSE                   # License for the project
├── README.md                 # Main README file
