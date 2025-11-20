# 🪨 Project-1: Sonar Rock & Mine Prediction

## 🌟 Project Summary
This project utilizes **sonar returns data** to build a **Machine Learning Classification Model** capable of distinguishing between a metallic **Mine ('M')** and a non-metallic **Rock ('R')**.  
The model uses **60 normalized features** representing the energy content at different frequency bands.

---

## 🎯 Objective
The main goal is to accurately classify objects scanned by sonar into one of two classes:

- **M → Mine**
- **R → Rock**

This classification is performed using a **Logistic Regression** algorithm.

---

## 🛠️ Technologies and Libraries Used

| Library | Purpose |
|--------|---------|
| **numpy** | Numerical operations |
| **pandas** | Data loading & manipulation |
| **sklearn (Scikit-learn)** | ML model, train/test split, evaluation |
| LogisticRegression | Model implementation |
| train_test_split | Data splitting |
| accuracy_score | Model accuracy evaluation |

---

## 📊 Dataset Details (Sonar Data)

- **Total Rows:** 208  
- **Total Features:** 60 (Columns 0–59), all `float64` values  
- **Target Column (60):**  
  - `M` → Mine  
  - `R` → Rock  

### 📌 Class Distribution:
- **Mine (M):** 111 instances  
- **Rock (R):** 97 instances  

*(Dataset is slightly imbalanced)*

---

## ⚙️ Model Performance — Logistic Regression

The dataset was split using a **stratified approach** for balanced training and testing.

- **Test Size:** 10%  
- **random_state:** 1  

### 📈 Accuracy Scores

| Metric | Score |
|--------|--------|
| **Training Accuracy** | **83.42%** |
| **Test Accuracy** | **76.19%** |

---

## 📌 How It Works
1. Load sonar dataset  
2. Separate features & target label  
3. Split into train & test sets  
4. Train Logistic Regression  
5. Predict & evaluate accuracy  

---


## ✔️ Conclusion
The Logistic Regression model performs well on sonar data, achieving a decent accuracy on both training and testing datasets.  
You can further improve the model using scaling, PCA, or advanced algorithms (SVM, Random Forest, etc).

---

## 🙌 Author
**Abhinav Singh**  
GitHub: https://github.com/Abhi2701singh  
