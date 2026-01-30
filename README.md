# Disease Prediction from Medical Data

This project predicts the **probability of disease** based on patient medical data using machine learning classification models.  
The final system provides **risk-level classification** and a **visual dashboard** to support probability-based medical decision making.

---

##  Objective
To predict the **possibility (probability)** of disease in patients using structured medical data and classify patients into **Low, Medium, or High Risk** categories.

---

##  Dataset
- **Name:** Breast Cancer Wisconsin (Diagnostic)
- **Source:** UCI Machine Learning Repository  
  https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
- **Description:**  
  The dataset contains numerical features extracted from Fine Needle Aspirate (FNA) images of breast masses.  
  It includes **569 samples** with **30 medical features**.

---

##  Models Used
- Logistic Regression  
- Random Forest (**Final Selected Model**)  
- Support Vector Machine (SVM)  
- XGBoost  

---

##  Methodology
1. Dataset loading and exploration  
2. Target encoding (Benign / Malignant)  
3. Train–test split and feature scaling  
4. Model training and evaluation  
5. Probability-based disease prediction  
6. Risk level classification  
7. Visualization using a dashboard  

---

##  Evaluation Metrics
- Accuracy  
- Precision, Recall, F1-score  
- ROC-AUC Score  
- Confusion Matrix  

---

##  Results
- Random Forest achieved the **best ROC-AUC score**
- The model predicts **disease probability** for each patient
- Patients are classified into:
  - Low Risk
  - Medium Risk
  - High Risk
- Results are visualized using a **Disease Risk Prediction Dashboard**

---

##  Dashboard
The dashboard visualizes:
- Disease probability distribution  
- Risk assessment table  
- ROC curve of the final model  
- Confusion matrix  

---

##  Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- XGBoost  
- ucimlrepo  

---

##  Repository Structure
CodeAlpha_Disease_Prediction/
│
├── Disease_Prediction_CodeAlpha_task_4.ipynb
├── README.md
├── requirements.txt
│
└── outputs/
├── dashboard.png
├── probability_table.png

---

##  Conclusion
This project demonstrates how machine learning models can be used to predict the **probability of disease** and assist in **risk-based medical decision support** using structured patient data.

