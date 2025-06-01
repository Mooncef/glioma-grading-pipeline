# 🧬 Glioma Grading – ML & Deep Learning Pipeline

**Brain Tumor Classification (LGG vs GBM) using Clinical & Genetic Features with Machine Learning and Artificial Neural Networks.**

---

## Objective

Design an AI system to classify brain tumors (Glioma) into:
- **LGG**: Lower Grade Glioma
- **GBM**: Glioblastoma Multiforme

Based on:
- **Clinical data**: Gender, Age, Race
- **Genetic mutations**: Top 20 most mutated genes from TCGA

## What This Project Covers

### `glioma_grading1.ipynb`
Machine Learning Approach:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

Preprocessing:
- Missing data handling
- Feature encoding
- Scaling

Modeling:
- 80/20 train-test split
- GridSearchCV
- ROC, Precision-Recall, Confusion Matrix
- Feature importance from tree-based models

### `glioma_grading2.ipynb`
Deep Learning Approach:
- ANN using **Keras Sequential model**
- Multiple Dense layers with ReLU and Softmax
- Categorical encoding and data normalization
- Evaluation with accuracy & loss curves
- Comparison with classical ML models

## Files Included

| File                  | Description                                         |
|-----------------------|-----------------------------------------------------|
| `glioma_grading1.ipynb`   | Classical ML models for glioma classification       |
| `glioma_grading2.ipynb`     | Deep Learning approach using ANN (Keras)            |
| `TCGA_GBM_LGG_Mutations_all.csv` | Training dataset from TCGA (UCI source)        |
| `test.xlsx`           | Test dataset to evaluate final predictions          |
| `instructions.pdf`    | Problem description and task details                |

---

## 🧑‍💻 Author

**Moncef Berkoun**  
🎓 MSc Artificial Intelligence & Technological Innovation – UTBM  
🔗 [LinkedIn](https://www.linkedin.com/in/moncef-berkoun/)  
📧 moncef.berkoun@gmail.com  
