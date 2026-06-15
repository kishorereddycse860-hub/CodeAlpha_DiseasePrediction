# Disease Prediction from Medical Data

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-1.6+-red.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

## 📌 Project Overview
This project is part of the **CodeAlpha Machine Learning Internship — Task 4**.
It predicts the possibility of heart disease based on patient medical data using
multiple classification algorithms and compares their performance.

## 🗂 Dataset
- **Name:** Heart Disease Dataset
- **Source:** Kaggle / UCI ML Repository
- **Size:** 1,025 patients
- **Features:** 13 (age, sex, chest pain, blood pressure, cholesterol, etc.)
- **Target:** 0 = No Heart Disease, 1 = Heart Disease

## 🤖 Models Used
| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | ~85% | ~92% |
| Random Forest | ~98% | ~100% |
| XGBoost | ~98% | ~99% |

## 📊 Results
- **Best Model:** Random Forest
- **Best ROC-AUC:** 100.00%
- Metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC

## 📁 Project Structure

## ⚙️ Installation & Usage
```bash
# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

# Run the script
python code__disease_prediction.py
```

## 📈 Output Files
- `target_distribution.png` — Target class distribution
- `roc_curve.png` — ROC Curve comparison of all models
- `feature_importance_rf.png` — Random Forest feature importance
- `feature_importance_xgb.png` — XGBoost feature importance
- `confusion_matrix.png` — Confusion matrices for all models
- `model_comparison.png` — All metrics compared in bar chart
- `model/best_model.pkl` — Saved best model
- `model/scaler.pkl` — Saved scaler

## 🙋 Author
**Kishore Reddy Gayam**
- 🎓 B.Tech CSE (AI/ML) — Marwadi University
- 💼 ML Intern @ CodeAlpha
- 🔗 [LinkedIn](https://linkedin.com/in/kishore-reddy-gayam-867254316)
- 🐙 [GitHub](https://github.com/kishorereddycse860-hub)
