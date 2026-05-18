# Diabetes Detection and Prediction Using the Machine Learning Paradigm

> 📄 **This project is based on a research paper published at IEEE — [View on IEEE Xplore](https://ieeexplore.ieee.org/document/11011335)**

---

## 📌 Overview

Diabetes mellitus is a chronic metabolic disorder with over 537 million affected adults worldwide. Early detection is critical to preventing complications such as cardiovascular disease, kidney failure, and nerve damage.

This project applies and benchmarks **7 supervised machine learning algorithms** on a dataset of 50,000 patient records, incorporating both traditional health indicators and **gender-specific factors** (hormonal influences, BMI thresholds, gestational history) to build a robust and inclusive diabetes prediction system.

---

## 📄 Research Publication

| Field | Details |
|---|---|
| **Title** | Diabetes Detection and Prediction Using the Machine Learning Paradigm |
| **Authors** | Saksham Gupta, Aarush Wali, Gandharv Kaloo, **Archit Bali**, Palvi Sharma |
| **Institution** | Model Institute of Engineering & Technology, Jammu, India |
| **Published in** | IEEE Xplore (2025) |
| **DOI / Link** | [https://ieeexplore.ieee.org/document/11011335](https://ieeexplore.ieee.org/document/11011335) |

---

## 🗂️ Dataset

- **Source:** Kaggle (merged & processed)
- **Size:** 50,000 entries, 12 attributes
- **Split:** 80% training (40,000) / 20% testing (10,000)

**Features:**
| Feature | Description |
|---|---|
| Gender | Male / Female (encoded: 1 / 0) |
| Age | Patient age in years |
| Hypertension | Presence of hypertension |
| Heart Disease | Presence of heart disease |
| Smoking History | Categorical smoking status |
| BMI | Body Mass Index |
| HbA1c Level | Glycated haemoglobin level |
| Blood Glucose Level | Fasting blood glucose |
| Pregnancies | Number of pregnancies |
| Genetics | Genetic predisposition flag |
| Cholesterol | Cholesterol level |
| Blood Pressure | Diastolic blood pressure |

---

## 🛠️ Tech Stack

- **Language:** Python 3
- **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, XGBoost
- **Preprocessing:** Min-Max Normalization, Label Encoding, Standard Scaler
- **Environment:** Jupyter Notebook

---

## 🤖 ML Algorithms Benchmarked

| Algorithm | Accuracy | Precision | Recall | F1-Score |
|---|---|---|---|---|
| Logistic Regression | 0.81 | 0.84 | 0.94 | 0.89 |
| Decision Tree | 0.78 | 0.87 | 0.85 | 0.86 |
| K-Nearest Neighbor | 0.82 | 0.84 | 0.96 | 0.89 |
| Random Forest | 0.85 | 0.85 | 0.99 | 0.92 |
| Naive Bayes | 0.80 | 0.85 | 0.91 | 0.88 |
| XGBoost | 0.85 | 0.86 | 0.98 | 0.91 |
| **Gradient Boosting** | **0.86** | **0.85** | **0.98** | **0.92** |

**Gradient Boosting** achieved the best performance with **86% accuracy** and an AUC of **0.84**, demonstrating strong generalization with minimal overfitting.

---

## 🔑 Key Findings

- **Gradient Boosting & XGBoost** outperformed all other models due to ensemble learning and regularization
- **Gender-specific factors** (BMI thresholds, hormonal variations, gestational history) significantly improved prediction reliability
- **Blood glucose level (0.26)**, **cholesterol (0.32)**, and **HbA1c (0.26)** were the strongest predictors of diabetes
- **Gender and pregnancy** showed a strong negative correlation (-0.85), validating the importance of gender-aware modeling

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/architinit/Diabetes-Detection-and-Prediction-System-.git
   cd Diabetes-Detection-and-Prediction-System-
   ```

2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xgboost jupyter
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Main.ipynb
   ```

---

## 👤 Author

**Archit Bali**  
B.Tech CSE (AI/ML) — Model Institute of Engineering and Technology, Jammu  
📧 archit.init@gmail.com  
🔗 [GitHub](https://github.com/architinit) | [LinkedIn](https://linkedin.com/in/archit-bali)

---

## 📜 Citation

If you use this work, please cite:

```
S. Gupta, A. Wali, G. Kaloo, A. Bali, P. Sharma,
"Diabetes Detection and Prediction Using the Machine Learning Paradigm,"
IEEE Xplore, 2025. https://ieeexplore.ieee.org/document/11011335
```

---

⭐ If you found this useful, consider starring the repository!
