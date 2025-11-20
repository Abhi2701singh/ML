# 🩺 Diabetes Prediction Model

## 📘 Project Overview
This project implements a **Machine Learning Classification Model** to predict the presence of **diabetes** using the **Pima Indians Diabetes Dataset**.  
A **Support Vector Machine (SVM)** classifier with a **linear kernel** is used to identify whether a person is **Diabetic (1)** or **Non-Diabetic (0)** based on important health indicators.

---

## 🎯 Core Objective
To determine if an individual is diabetic by analyzing various diagnostic measurements.  
This is a **binary classification problem** where:

- **0 → Non-Diabetic**
- **1 → Diabetic**

---

## 🛠️ Technologies and Libraries Used
The project uses essential tools from the Python ML ecosystem:

| Library | Purpose |
|--------|---------|
| **numpy** | Numerical operations |
| **pandas** | Data loading & analysis |
| **StandardScaler** | Data standardization (important for SVM) |
| **train_test_split** | Dataset splitting |
| **SVC (Support Vector Classifier)** | Machine learning model (kernel='linear') |
| **accuracy_score** | Model performance evaluation |

---

## 📊 Dataset Details
- **Dataset File:** `diabetes.csv`  
- **Total Records:** 768 data points  
- **Columns:** 9 (8 input features + 1 output label)  

### 📌 Outcome Distribution:
- **0 → Non-Diabetic:** 500 cases  
- **1 → Diabetic:** 268 cases  

### 📋 Feature Descriptions

| Feature | Description |
|--------|-------------|
| **Pregnancies** | Number of pregnancies |
| **Glucose** | Plasma glucose concentration |
| **BloodPressure** | Diastolic blood pressure |
| **SkinThickness** | Triceps skinfold thickness |
| **Insulin** | 2-hour serum insulin |
| **BMI** | Body mass index |
| **DiabetesPedigreeFunction** | Diabetes pedigree function |
| **Age** | Age in years |
| **Outcome** | Target label (0 or 1) |

---

## ⚙️ Model & Training Details (SVM)
- **Algorithm:** Support Vector Machine (SVC)  
- **Kernel:** Linear  
- **Data Standardization:** Yes (StandardScaler)  
- **Train-Test Split:** 70% training — 30% testing  
- **Stratified Split:** Yes (keeps class ratio balanced)

---

## 📈 Model Performance

| Dataset | Accuracy |
|--------|----------|
| **Training Accuracy** | ≈ **78.21%** |
| **Testing Accuracy** | ≈ **77.49%** |

---

## ▶️ How to Run

1. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn
   ```

2. Run the Jupyter Notebook:

   ```bash
   jupyter notebook diabetes.ipynb
   ```

---

## ✔️ Conclusion

The SVM model with a linear kernel delivers strong performance for a binary medical prediction task.
With proper scaling and balanced splitting, it achieves **~77% accuracy**, making it a reliable baseline for diabetes prediction.

---

## 👨‍💻 Author

**Abhinav Singh**  
GitHub: https://github.com/Abhi2701singh


