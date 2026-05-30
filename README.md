# 🩺 Diabetes Prediction Using Machine Learning

This project predicts whether a patient is likely to have diabetes based on medical attributes such as glucose level, BMI, age, blood pressure, and other health indicators.

---

## 📌 Project Overview

The goal of this project is to build and compare multiple machine learning models for diabetes prediction and identify the best-performing model.

The project includes:

- Data preprocessing
- Missing value handling
- Duplicate removal
- Feature scaling
- Model training
- Model comparison
- Feature importance analysis
- Diabetes prediction

---

## 📊 Dataset Information

The dataset contains medical information of patients and a target column named **Outcome**.

### Features

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

### Target Variable

- Outcome
  - 0 = No Diabetes
  - 1 = Diabetes

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Replaced invalid zero values with NaN
- Filled missing values using median values
- Removed duplicate records
- Applied StandardScaler for feature scaling
- Split data into training and testing sets

---

## 🤖 Machine Learning Models

The following models were trained and compared:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy Score
- Classification Report

The best-performing model was selected based on test accuracy.

---

## 🔍 Feature Importance

Feature importance analysis was performed using the Random Forest model to identify the most influential features affecting diabetes prediction.

Common important features include:

- Glucose
- BMI
- Age
- DiabetesPedigreeFunction

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/zunaira-hameed/diabetes-detection/
```

### Install Dependencies

```bash
pip install pandas numpy scikit-learn
```

### Run Notebook

Open the Jupyter Notebook and run all cells sequentially.

---

## 📁 Project Structure

```text
├── diabetes.csv
├── diabetes_prediction.ipynb
├── README.md
```

---

## 🎯 Project Objective

To compare multiple machine learning algorithms and build an effective model for predicting diabetes using patient health data.

---

## 👩‍💻 Author

Zunaira Hameed

- Python Developer
- Machine Learning Enthusiast

---
⭐ If you found this project useful, consider giving it a star.
