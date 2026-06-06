# Disease Prediction from Medical Data Using Machine Learning

## Overview

This project develops a Machine Learning-based Disease Prediction System capable of identifying disease outcomes using structured medical data. The model analyzes patient health parameters and predicts whether a disease is present or absent.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, feature scaling, model training, evaluation, visualization, and prediction.

---

## Features

* Medical data preprocessing
* Feature scaling using StandardScaler
* Multiple classification algorithms
* Disease prediction
* Accuracy comparison
* Confusion matrix visualization
* Classification report generation
* Healthcare AI application

---

## Dataset

The project uses a medical dataset containing patient health-related features.

### Dataset Features

* Age
* Medical Measurements
* Diagnostic Features
* Clinical Indicators

### Target Variable

* 0 → Disease Absent
* 1 → Disease Present

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Machine Learning Algorithms

### Logistic Regression

A statistical classification algorithm used for binary prediction problems.

### Support Vector Machine (SVM)

Creates an optimal decision boundary to separate disease classes.

### Random Forest

An ensemble learning technique that combines multiple decision trees to improve prediction accuracy.

---

## Project Workflow

```text
Dataset Collection
        ↓
Data Preprocessing
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Disease Prediction
```

---

## Model Performance

| Model                        | Accuracy |
| ---------------------------- | -------- |
| Logistic Regression          | 97.37%   |
| Support Vector Machine (SVM) | 98.25%   |
| Random Forest                | 96.49%   |

### Best Performing Model

🏆 **Support Vector Machine (SVM)** achieved the highest accuracy of **98.25%**.

---

## Confusion Matrix (Random Forest)

| Actual / Predicted | 0  | 1  |
| ------------------ | -- | -- |
| 0                  | 40 | 3  |
| 1                  | 1  | 70 |

---

## Classification Report

| Class | Precision | Recall | F1-Score |
| ----- | --------- | ------ | -------- |
| 0     | 0.98      | 0.93   | 0.95     |
| 1     | 0.96      | 0.99   | 0.97     |

### Overall Accuracy

**96%**

---

## Results

The implemented machine learning models achieved excellent predictive performance.

Key Findings:

* SVM delivered the highest accuracy.
* Random Forest achieved strong classification performance with very low false negatives.
* Logistic Regression provided reliable baseline results.
* The system demonstrates the effectiveness of Machine Learning in healthcare prediction tasks.

---

## Applications

* Early Disease Detection
* Clinical Decision Support
* Healthcare Analytics
* Risk Assessment Systems
* Preventive Healthcare Programs
* Medical Research

---

## Project Structure

```text
Disease_Prediction_Project/
│
├── Disease_Prediction.ipynb
├── dataset.csv
├── README.md
├── Disease_Prediction_Report.docx
├── requirements.txt
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Disease-Prediction-ML.git
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Future Enhancements

* Streamlit Web Application
* Real-Time Disease Prediction
* Multiple Disease Classification
* Integration with Hospital Information Systems
* Explainable AI for Healthcare

---

## Conclusion

This project successfully demonstrates the use of Machine Learning techniques for disease prediction using medical data. The developed system achieved a maximum accuracy of **98.25% using Support Vector Machine (SVM)**, highlighting the potential of AI-powered healthcare solutions for assisting medical diagnosis and decision-making.

---

## References

1. Scikit-Learn Documentation
2. Python Documentation
3. UCI Machine Learning Repository
4. Healthcare Machine Learning Research Papers
5. Artificial Intelligence in Healthcare Literature
