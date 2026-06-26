# 🔐 Cyber Security Threat Detection — ML Classification

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SMOTE](https://img.shields.io/badge/SMOTE-Class%20Imbalance-orange?style=flat-square)
![Accuracy](https://img.shields.io/badge/Accuracy-95%25-brightgreen?style=flat-square)

> ML pipeline for network intrusion detection — classifying network traffic as normal or malicious using Random Forest with SMOTE, achieving 95% accuracy.

---

## 📌 Problem Statement
Cyber attacks are growing in frequency and sophistication. This project builds an ML-based Intrusion Detection System (IDS) to automatically classify network traffic as benign or malicious, enabling faster threat response and reducing security analyst workload.

## 🎯 Results

| Metric | Score |
|--------|-------|
| **Accuracy** | **95%** |
| Precision (Attack class) | 93% |
| Recall (Attack class) | 94% |
| F1-Score (Attack class) | 93% |
| Model | Random Forest Classifier |
| Imbalance Handling | SMOTE (Synthetic Minority Oversampling) |
| Task | Binary + Multiclass Classification |

## 🛠️ Tech Stack
- **Language:** Python
- **ML:** Scikit-learn, Random Forest
- **Imbalance Handling:** SMOTE (imbalanced-learn)
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Project Structure
```
cyber-security-threat-detection-ml/
├── Cyber_sectrity_project/
│   └── Cyber_Security_Project.zip   # Dataset & notebooks
├── requirements.txt
└── README.md
```

## 🚀 How to Run
```bash
git clone https://github.com/shreesneha056-gif/cyber-security-threat-detection-ml.git
cd cyber-security-threat-detection-ml
pip install -r requirements.txt
# Extract zip and launch:
jupyter notebook
```

## 📊 Pipeline Overview
1. **Data Loading & EDA** — Explore network traffic telemetry features
2. **Preprocessing** — Encode categorical features, normalize numerics
3. **Class Imbalance** — Apply SMOTE to oversample minority attack class
4. **Model Training** — Random Forest classifier (binary + multiclass)
5. **Evaluation** — 95% accuracy, precision/recall/F1 per class, confusion matrix
6. **Result** — Attack-class recall improved by ~25% after SMOTE vs baseline

---
📫 [LinkedIn](https://www.linkedin.com/in/sneha-shree-mu/) | [Portfolio](https://shreesneha056-gif.github.io/portfolio_website/) | [GitHub](https://github.com/shreesneha056-gif)
