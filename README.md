# 🚨 Disaster Tweets Classification (NLP)

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project focuses on **classifying tweets** to determine whether they describe a **real disaster** or not.  
It is based on the Kaggle **“Disaster Tweets” NLP challenge**.

The solution uses **TF-IDF feature extraction** combined with **Logistic Regression**, optimized using **GridSearchCV**.

---

## 📊 Dataset
The dataset contains:
- **text** — tweet content  
- **keyword** — disaster-related keyword  
- **target**
  - `1` → real disaster  
  - `0` → not a disaster  

---

## 🧠 Methodology
1. Text preprocessing using **TF-IDF**
2. Separate vectorization of:
   - tweet text  
   - keyword feature
3. Feature combination using **sparse matrix stacking**
4. Model training using **Logistic Regression**
5. Hyperparameter tuning with **GridSearchCV**
6. Prediction and submission file generation

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- SciPy
- Matplotlib
- Seaborn
