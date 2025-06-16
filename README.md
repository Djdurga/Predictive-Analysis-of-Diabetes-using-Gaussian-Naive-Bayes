# 🧪 Predictive Analysis of Diabetes using Gaussian Naive Bayes

## 📌 Project Overview

This project uses the **Gaussian Naive Bayes (GNB)** classification algorithm to predict whether a person is likely to have diabetes based on diagnostic measurements. The project is based on the **Pima Indians Diabetes Dataset**, which is commonly used for binary classification tasks in healthcare analytics.

---

## 🎯 Objective

To build a predictive model using **Gaussian Naive Bayes** to classify patients as diabetic (`Outcome = 1`) or non-diabetic (`Outcome = 0`) based on health-related features.

---

## 🧬 Dataset Information

- **Source**: [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Records**: 768
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**: `Outcome` (Binary — 0: Non-Diabetic, 1: Diabetic)

---

## 🧠 Why Gaussian Naive Bayes?

- Assumes features follow a **normal (Gaussian) distribution**
- Fast and efficient for high-dimensional data
- Suitable for medical prediction problems with continuous variables
- Performs well with small datasets

---

## ⚙️ Workflow

1. **Data Loading & Exploration**
   - Load CSV using `pandas`
   - Initial inspection of missing/zero values

2. **Data Preprocessing**
   - Replace invalid zeros in features like Glucose, Insulin, BMI, etc., with median values

3. **Model Building**
   - Split dataset into training and test sets
   - Apply **GaussianNB()** from `sklearn.naive_bayes`

4. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve & AUC Score

---

## 📊 Results Snapshot

| Metric        | Value (Example) |
|---------------|-----------------|
| Accuracy      | 76.5%           |
| Precision     | 74.3%           |
| Recall        | 70.2%           |
| F1-Score      | 72.2%           |
| AUC Score     | 81.3%           |

*(Replace these values with your actual outputs)*

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 💻 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/diabetes-gnb-prediction.git
cd diabetes-gnb-prediction
