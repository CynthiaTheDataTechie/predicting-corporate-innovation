# 🧠 Predicting Corporate Innovation: A Comparative Study of Logistic Regression and Random Forest

This repository explores the use of machine learning models to predict corporate innovation. By comparing **Logistic Regression** and **Random Forest**, we uncover the strengths and weaknesses of each approach for classifying whether a company is innovative based on a given dataset.

---

## 📚 Table of Contents
- [📚 Summary](#-summary)
- [📊 Dataset](#-dataset)
- [🔍 Key Findings](#-key-findings)
- [📈 Results](#-results)
- [🛠️ How to Use](#️-how-to-use)
- [📂 Folder Structure](#folder-structure)
- [🎥 YouTube Video Walkthrough](#-youtube-video-walkthrough)
- [📚 Read the Full Article](#-read-the-full-article)
- [📜 License](#-license)
- [🌟 Acknowledgments](#-acknowledgments)
- [📫 Connect With Me](#-connect-with-me)


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
3. `Size`: Total number of employees in the company and Market presence.
4. `Investment`: Percentage of investment made by the company.
5. `Service Launch`: The frequency and capability of the company to provide new services/products.
6. `Training`: The level of training provided to employees.
7. `Bonus System`: The presence of bonus systems/incentives to employees.

These features were preprocessed (e.g., scaling, encoding) and analyzed to determine their impact on predicting corporate innovation.
Dataset Source: [World Bank Enterprise Surveys](http://www.enterprisesurveys.org)
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
| Logistic Regression | 0.59     | 0.57      | 0.65   | 0.61     | 0.64     | 0.69 |
| Random Forest       | 0.81     | 0.76      | 0.90   | 0.83     | 0.49     | 0.86 |

- **Key Insight**:- **Accuracy**: Random Forest achieves **81%**, outperforming Logistic Regression's **59%**.
- **Precision**: Random Forest achieves **0.76**, reducing false positives compared to Logistic Regression (**0.57**).
- **Recall**: Random Forest detects **90%** of innovative companies, significantly better than Logistic Regression (**65%**).
- **F1-Score**: Random Forest balances precision and recall with a high score of **0.83**, compared to Logistic Regression's **0.61**.
- **Log-Loss**: Random Forest achieves a lower log-loss (**0.49**) than Logistic Regression (**0.64**), indicating more accurate probability predictions.
- **AUC**: Random Forest demonstrates better class distinction with an AUC of **0.86**, compared to Logistic Regression’s **0.69**.

**Conclusion**: Random Forest outperforms Logistic Regression in all metrics, making it the preferred model for predicting corporate innovation.

---

## 🛠️ How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/CynthiaTheDataTechie/predicting-corporate-innovation.git
   cd predicting-corporate-innovation
   pip install -r requirements.txt
   jupyter notebook analysis.ipynb
## Folder Structure
predicting-corporate-innovation/
├── notebooks/                 # Jupyter notebooks for the project
│   ├── dummyvar.ipynb         # Main notebook for the project
├── results/                   # Analysis outputs
│   ├── figures/               # Saved plots (e.g., ROC curves, feature importance)
│   ├── README.md              # Documentation for results
├── requirements.txt           # Python dependencies
├── LICENSE                    # License for the project
├── README.md                  # Main README file
## 🎥 YouTube Video Walkthrough

A detailed video walkthrough of this project is available on my YouTube channel. The video covers:
- **Dataset Preparation**: Preprocessing steps like cleaning, encoding, and scaling.
- **Feature Engineering**: Selecting and engineering relevant features.
- **Model Building**: Training Logistic Regression and Random Forest models.
- **Evaluation Metrics**: Comparing models using accuracy, precision, recall, F1-score, log-loss, and AUC.
- **Results and Insights**: Visualizing key results and deriving actionable insights.

[![YouTube Video Walkthrough]coming soon

> 📌 The walkthrough provides step-by-step guidance, ensuring you can replicate the results or adapt the approach for similar projects.

---
## 📚 Read the Full Article

For a detailed walkthrough of the methodology, insights, and visualizations, check out the full blog post:

[**Predicting Corporate Innovation: A Comparative Study of Logistic Regression and Random Forest**](https://medium.com/@cynthiaakiotu/predicting-corporate-innovation-a-comparative-study-of-logistic-regression-and-random-forest-4cb12ecb9a24)

> 📌 This article delves into the project in greater depth, covering the data preprocessing steps, feature engineering, model building, evaluation metrics, and key insights.

## 📜 License

This project is licensed under the **MIT License**.

For more details, see the [LICENSE](LICENSE) file in this repository.
## 🌟 Acknowledgments

I would like to thank the data science community for their continuous support and inspiration. Special thanks to:
- Everyone who provided feedback and guidance during this project.
- The creators of the tools and libraries used in this project, including Python, Scikit-learn, Pandas, Matplotlib, and more.

### Reference:
- Dataset Source: [World Bank Enterprise Surveys](http://www.enterprisesurveys.org)

This project is a testament to the power of collaboration and the open-source community. Thank you all! 😊


## 📫 Connect With Me

Feel free to connect with me for more projects, collaborations, or discussions:

- **YouTube Channel**: [Subscribe Here](https://www.youtube.com/@CynthiaTheDataTechie)
- **LinkedIn**: [Connect with Me](https://www.linkedin.com/in/cynthia-akiotu-7b695aa9/)
- **Medium Blog**: [Read My Articles](https://medium.com/@cynthiaakiotu)
