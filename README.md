# 📊 Sentiment Analysis of Danantara Program (Twitter Data)

This project aims to analyze public sentiment toward the **Danantara program** using data collected from platform X (Twitter).  
The study focuses on handling imbalanced data using **SMOTE** and evaluating different machine learning models.

---

## 🎯 Objective

- Analyze public sentiment from social media (Twitter/X)
- Compare performance of machine learning models:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Random Forest
- Evaluate the impact of SMOTE in different scenarios:
  - Without SMOTE
  - SMOTE before train-test split
  - SMOTE after train-test split

---

## 🧾 Dataset

- Source: Twitter (X)
- Period: February – March 2025
- Total Data: 10,506 tweets
- Method: Web scraping using Twikit

---

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- NLTK

---

## 🔄 Workflow

1. Data Collection (Twitter Scraping)
2. Data Preprocessing
3. Feature Extraction using TF-IDF
4. Handling Imbalanced Data using SMOTE
5. Model Training
6. Model Evaluation

---

## 📊 Model Evaluation Results

### Naive Bayes Performance
![Naive Bayes](results/nb_comparison.png)

---

### Support Vector Machine Performance
![SVM](results/svm_comparison.png)

---

### Random Forest Performance
![Random Forest](results/rf_comparison.png)

---

## 💡 Key Findings

- Applying SMOTE improves model performance, especially for minority classes.
- Models trained with SMOTE after train-test split provide more reliable evaluation.
- Using SMOTE before splitting the data can lead to overly optimistic results due to potential data leakage.
- Random Forest and SVM achieved the highest performance among the tested models.

---

## 🚀 How to Run

```bash
pip install -r requirements.txt

Run the notebooks in order:

Data Collection
Data Preprocessing
Modeling