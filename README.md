# 🧠 Predicting Corporate Innovation: A Comparative Study of Logistic Regression and Random Forest

This repository explores the use of machine learning models to predict corporate innovation. By comparing **Logistic Regression** and **Random Forest**, we uncover the strengths and weaknesses of each approach for classifying whether a company is innovative based on a given dataset.

---

## 📚 Table of Contents
1. [Summary](#summary)
2. [Dataset](#dataset)
3. [Key Findings](#key-findings)
4. [Results](#results)
5. [How to Use](#how-to-use)
6. [Folder Structure](#folder-structure)
7. [YouTube Video Walkthrough](#youtube-video-walkthrough)
8. [Read the Full Article](#read-the-full-article)
9. [License](#license)
10. [Connect With Me](#connect-with-me)
11. [Acknowledgments](#acknowledgments)

---

## 📚 Summary

Predicting corporate innovation is crucial for businesses looking to stay competitive in dynamic markets. This project delves into:
- **Dataset Preparation**: Handling missing data, encoding categorical variables, and feature scaling.
- **Feature Engineering**: Selecting features most relevant to predicting innovation.
- **Model Training and Evaluation**:
  - Logistic Regression: A linear model suited for interpretability.
  - Random Forest: A non-linear model that excels in handling complex data patterns.
- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score, Log-Loss, and AUC (Area Under Curve).

The study provides insights into which model performs better based on various evaluation metrics and the trade-offs between interpretability and performance.

---

## 📊 Dataset

The dataset used in this study contains the following variables:

### **Target Variable**
- `Innovative`: A binary indicator (1 = Innovative, 0 = Not Innovative) specifying whether a company is considered innovative.

### **Input Features**
1. `Revenue`: Annual revenue of the company.
2. `R&D Expenditure`: Expenditure on research and development activities.
3. `Size`: Total number of employees in the company and market presence.
4. `Investment`: Percentage of the market control.
5. `Bonus System`: A measure of bonus systems and incentive offered to employees.
6. `Training`: The extent of training programs provided by employees (1–10 scale).
7. `Service Launch`: The frequency of companies to launch new services/products.

These features were preprocessed (e.g., scaling, encoding) and analyzed to determine their impact on predicting corporate innovation.

---

## 🔍 Key Findings

- **Logistic Regression**:
  - Strengths:
    - Simple and interpretable.
    - Handles linear relationships effectively.
  - Limitations:
    - Struggles with non-linear data patterns.
  - Best suited for scenarios where model interpretability is critical.

- **Random Forest**:
  - Strengths:
    - Handles non-linear relationships and complex interactions between features.
    - Robust to overfitting with proper hyperparameter tuning.
  - Limitations:
    - Less interpretable than Logistic Regression.
  - Ideal for scenarios requiring high accuracy and robustness.

---

## 📈 Results

| Model               | Accuracy | Precision | Recall | F1-Score | Log-Loss | AUC  |
|---------------------|----------|-----------|--------|----------|----------|------|
| Logistic Regression | 0.59      | 0.57      | 0.65   | 0.61     | 0.64     | 0.69 |
| Random Forest       | 0.81      | 0.76      | 0.90   | 0.83     | 0.49     | 0.86 |

- **Key Insight**: Random Forest outperformed Logistic Regression in terms of accuracy and robustness to complex data patterns. However, Logistic Regression remains a strong choice when interpretability is essential.

---

## 🛠️ How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CynthiaTheDataTechie/predicting-corporate-innovation.git
   cd predicting-corporate-innovation
   pip install -r requirements.txt
   jupyter notebook analysis.ipynb
   predicting-corporate-innovation/
predicting-corporate-innovation/
├── notebooks/                 # Jupyter notebooks for the project
│   ├── dummyvar.ipynb         # Main notebook for the project
├── results/                   # Analysis outputs
│   ├── figures/               # Saved plots (e.g., ROC curves, feature importance)
│   ├── README.md              # Documentation for results
├── requirements.txt           # Python dependencies
├── LICENSE                    # License for the project
├── README.md                  # Main README file
