
# 🍷 Wine Quality Classification Project

---

## 📚 Project Overview
This project aims to classify the quality of wine samples using machine learning models. We work through the complete ML pipeline: data preprocessing, modeling, evaluation, and reporting.

The dataset used is **WineQT.csv**, which contains physicochemical properties of wine and their corresponding quality scores.

---

## 🏁 Milestones Breakdown

### ✅ Milestone 1: Data Preprocessing and Exploratory Data Analysis (EDA)

- **Tasks:**
  - Handled missing values, duplicates, and outliers.
  - Encoded categorical features (if any) and scaled numerical features.
  - Created visualizations:
    - Histograms
    - Boxplots
    - Correlation heatmaps
  - Summarized key insights and detected patterns or anomalies in the dataset.

- **Deliverables:**
  - Jupyter Notebook documenting:
    - Preprocessing steps
    - Summary statistics
    - EDA visualizations
    - Key findings

---

### ✅ Milestone 2: Modeling

- **Tasks:**
  - Selected and trained the following models:

Random Forest

SGD Classifier

Support Vector Classifier (SVC)


Each was evaluated using test data and 5-fold cross-validation.
We tuned hyperparameters for SVC and Random Forest using GridSearchCV.



---


Random Forest performed the best overall in both F1-score and cross-validation accuracy.

SVC gave strong performance but was slightly behind in recall.

SGD had the lowest scores, indicating poor fit for this dataset.




---
  - Evaluated models based on accuracy, classification reports, and confusion matrices.

- **Deliverables:**
  - Jupyter Notebook containing:
    - Model training code
    - Tuning setups (GridSearchCV for traditional ML models)
    - Model performance evaluations
    - Visualizations of confusion matrices and ANN training curves

---

### ✅ Milestone 3: Model Evaluation and Interpretation

- **Tasks:**
  - Compared model performances systematically.
  - Visualized and interpreted:
    - Accuracy scores
    - Precision, Recall, F1-Score
    - Confusion matrices
  
  - Identified:
    - The best-performing model
    - Potential causes of misclassifications
    - Class imbalance issues

- **Deliverables:**
  - Evaluation tables summarizing metrics across models
  - Visualizations to interpret model behavior
  - Discussion of model strengths and weaknesses

---

### ✅ Milestone 4: Final Report and Conclusion

- **Tasks:**
  - Summarized:
    - Preprocessing techniques
    - Modeling choices
    - Evaluation results
  - Highlighted:
    - Final model selected for deployment or further development
    - Key insights about the dataset
    - Possible improvements for future work (e.g., handling class imbalance, advanced hyperparameter tuning, deep learning architectures)

- **Deliverables:**
  - Final comprehensive project report (or Jupyter Notebook)
  - Clear recommendations for future steps

---

## ⚙️ Project Structure

```bash
Wine-Quality-Classification/
│
├── README.md             # This file
├── WineQT.csv            # Dataset
├── milestone1_eda.ipynb   # Data Preprocessing & EDA
├── milestone2_modeling.ipynb  # Model training and tuning
├── milestone3_evaluation.ipynb # Model evaluation and comparison
├── milestone4_final_report.ipynb # Final conclusions and recommendations
└── requirements.txt      # List of required Python packages
```

---

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook / JupyterLab
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn


---



---

## ✨ Future Improvements

- Implement techniques to handle class imbalance (e.g., SMOTE, oversampling).
- Explore more powerful models like Gradient Boosting (XGBoost, LightGBM).
- Perform more extensive hyperparameter tuning with tools like Optuna or RandomizedSearchCV.
- Enhance ANN by introducing batch normalization, early stopping, and learning rate schedulers.

---

# 🚀 Thank you!

---

---

## COLLABORATORS
Maria Wangari Kanene.
Vincent Kimutai Ronoh.
Joy Melvine Okinyi.
Nasrudin Abdulahhi.
