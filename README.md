# Diabetes Prediction Using Support Vector Machine (SVM)

## 📌 Project Overview
This project focuses on predicting whether a person is diabetic or not using a **Support Vector Machine (SVM)** machine learning model.  
The model is trained on a medical dataset and helps in early detection of diabetes based on various health parameters.

---

## 📊 Dataset
- **Name:** PIMA Indians Diabetes Dataset
- **Source:** UCI Machine Learning Repository
- **Type:** Binary Classification
- **Target Variable:** Outcome  
  - `0` → Non-Diabetic  
  - `1` → Diabetic  

---

## 🧠 Machine Learning Model
- **Algorithm Used:** Support Vector Machine (SVM)
- **Kernel:** Linear / RBF (as used in implementation)
- **Data Scaling:** StandardScaler
- **Train-Test Split:** Used for model evaluation

---

## ⚙️ Workflow
1. Data Collection & Loading
2. Data Preprocessing
   - Handling missing/zero values
   - Feature scaling using StandardScaler
3. Model Training using SVM
4. Model Evaluation
5. Prediction on New Input Data

---

## 📈 Model Performance
- **Accuracy:** **79%**
- Accuracy is acceptable for a medical prediction dataset
- Focus is given to proper preprocessing and feature scaling

---

## 🛠️ Technologies Used
- Python
- Google Colab
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (if used for visualization)

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/shrreya24/diabetes-prediction-ml.git
