
# 📊 FASS – Fraud Adjusted Scalability Scoring

FASS is a **machine learning–based risk scoring system** designed to evaluate startup scalability under fraud exposure.
It predicts the probability of success and converts it into a **0–100 interpretable risk score**.

---

## 🚀 Features
- Logistic Regression–based risk scoring
- Leakage-safe preprocessing
- Probability calibration
- Risk bucket generation (Low / Medium / High)
- Designed for audit and governance use

---

## 🧠 Model Architecture

Startup Dataset  
→ Cleaning & Feature Engineering  
→ Logistic Regression (Balanced)  
→ Probability Calibration  
→ Risk Score (0–100)  
→ Risk Bucket Assignment  

---

## 🧰 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

---

## ⚙️ Setup
```bash
pip install -r requirements.txt
```

---

## ▶️ Run
```bash
python src/main.py
```

---

## 📊 Outputs
- output.csv
- threshold_sweep.csv
- reliability.png
- top_features.csv

---

## 📈 Risk Buckets
| Score | Risk |
|------|------|
| 0–33 | Low |
| 34–66 | Medium |
| 67–100 | High |

---

## 👤 Author
Vinay Kumar Nethavath  
B.Tech – IIIT Allahabad
