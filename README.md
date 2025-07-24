# HR-Model-Development-Project
IBM HR Analytics – Employee Attrition Project

This project is part of **Module 4 Assignment: Business Analytics Model**. It builds on the cleaned HR dataset from Milestone 1 and develops a classification model to predict employee attrition.

## **Project Overview**
This repository contains data, code, and outputs for my **Business Analytics coursework**, focused on employee attrition analysis using IBM HR Analytics data.

---

## **Contents**
- `HR Data Analysis` – Directory containing all Milestone 1 files 
- `HR_Model_Development.ipynb` – Jupyter Notebook with full implementation for Module 4  
- `output2/` – Directory containing saved plots and classification reports
- `HR_Attrition_Cleaned.csv` – Final cleaned and transformed dataset ready for modeling.
- `README.md` – Project summary and execution guide (this file)

---

## Step-by-Step Approach

1. Load and inspect cleaned dataset
2. Visualize target distribution (Attrition)
3. Split data into train and test sets
4. Apply standard scaling to numerical features
5. Train and evaluate 3 models:
   - Logistic Regression
   - Decision Tree
   - Random Forest
6. Compare results and select best model
7. Document findings and recommendations

---

## **Methods and Tools**
- **Language:** Python  
- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn
- **Tools:** Jupyter Notebook (Anaconda / VSCode / Colab)

---

## **Data Preparation (Milestone 1)**
- Imported and explored data.
- Cleaned missing values (none found) and encoded categorical columns.
- Engineered new features:
  - `TenureBucket`
  - `IncomePerJobLevel`
- Assessed outliers and correlations.

---

## **Model Development (Module 4)**
### **Objective:** Predict employee attrition (classification task).

**Models built:**
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

**Evaluation Metrics:**
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix (visualized)

## Outputs Saved

- **Classification Reports**:
  - `output2/Log_Reg_Classification_Report.txt`
  - `output2/Dec_Tre_Classification_Report.txt`
  - `output2/Ran_For_Classification_Report.txt`

- **Confusion Matrix Visuals**:
  - `output2/Log_Reg_Confusion_Matrix.png`
  - `output2/Dec_Tre_Confusion_Matrix.png`
  - `output2/Ran_For_Confusion_Matrix.png`

**Best model and final observations** are documented in `HR_Model_Development.ipynb`.

---

## **Ethics and Bias Consideration**
- Dataset is anonymized and used solely for educational purposes.
- Class imbalance was identified; strategies will be incorporated in further modeling to mitigate prediction bias.

---

## **Instructions to Clone and Run**

1. Clone the repository or unzip the file:  
   `Ruth_Nwawuzoh_BAN6800_Module_4_Assignment.zip`

2. Open `HR_Model_Development.ipynb` in Jupyter Notebook

3. Run all cells step-by-step to view the analysis, modeling, and evaluation

---

## Author

- **Ruth Nwawuzoh**  
- **Course:** BAN6800 – Business Analytics Capstone
- **Module 4 Assignment**  
- **Institution:** Nexford University

---
