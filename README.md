# 🧬 Glioma Grading with Clinical and Genomic Features

**Classifying Brain Tumor Types (LGG vs GBM) using Clinical and Mutation Data from TCGA.**

> A real-world ML pipeline from data preprocessing to model explainability – with clinical impact.

---

## 🎯 Project Overview

This project tackles a **high-stakes healthcare problem**: grading gliomas (brain tumors) as either  
**Lower Grade Glioma (LGG)** or **Glioblastoma Multiforme (GBM)** using:

- 🧑‍⚕️ **Clinical features**: Gender, Age at diagnosis, Race  
- 🧬 **Genetic markers**: 20 most frequently mutated genes

The goal is to design an **accurate and cost-efficient classifier** by identifying the **optimal subset of features** to support diagnosis and reduce unnecessary testing costs.

---

## 🚀 What I Did

✅ **End-to-end ML workflow**:
- **Data understanding**: distribution analysis, missing values, feature types
- **Preprocessing pipeline**: imputation, encoding, scaling
- **Train/test split**: 80/20 + stratification

✅ **Modeling & Evaluation**:
- Baseline: Logistic Regression, Decision Tree  
- Advanced: Random Forest, Support Vector Machine (SVM)  
- **Hyperparameter tuning**: GridSearchCV on 10-fold cross-validation
- **Model evaluation**: Accuracy, Precision, Recall, F1 Score, ROC/AUC, PR Curves

✅ **Explainability**:
- Feature importance analysis from decision tree & random forest
- Visual diagnostics (ROC, Precision-Recall, confusion matrices)

✅ **Deliverables**:
- Final predictions on new test data (`test.xlsx`)
- Complete code in reproducible Jupyter Notebook

---

## 📂 Files

| Filename                         | Description                                           |
|----------------------------------|-------------------------------------------------------|
| `HW1.ipynb`                      | Main notebook – full pipeline & analysis             |
| `TCGA_GBM_LGG_Mutations_all.csv`| Training data from TCGA (UCI ML Repo)                |
| `test.xlsx`                      | Blind test dataset to predict and evaluate           |
| `instructions.pdf`              | Full task description and evaluation criteria        |

---

## 🧑‍💻 Author

**Moncef Berkoun**  
🎓 UTBM | MSc in AI Engineering & Tech Entrepreneurship
🔗 [LinkedIn](https://www.linkedin.com/in/moncef-berkoun/)  
📧 moncef.berkoun@gmail.com  

