# ⚡ LightGBM vs XGBoost – Comparative Machine Learning Analysis (Titanic Dataset)

## 📖 Overview
This project demonstrates a **comparative study between LightGBM (LGBM)** and **XGBoost (XGBM)** using the **Titanic dataset**.  
It serves as an **example project** for understanding and evaluating two of the most powerful gradient boosting algorithms in machine learning.

The workflow covers **data exploration, preprocessing, model training, hyperparameter tuning**, and **comparative performance analysis**, helping to identify which algorithm achieves better prediction accuracy and generalization.

---

## 🎯 Objective
To compare and analyze the performance of **LightGBM** and **XGBoost** algorithms on the **Titanic dataset** and determine which model delivers better results for survival prediction.

---

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Loaded the Titanic dataset using **pandas**.  
- Examined **missing values**, outliers, and feature types.  
- Visualized distributions using **histograms**, **boxplots**, and **scatter plots**.  
- Analyzed relationships between key features (like `Age`, `Pclass`, `Sex`) and **Survival**.  
- Created **correlation heatmaps** to identify influential features.

---

### 2. Data Preprocessing
- Imputed missing values in numerical and categorical columns.  
- Encoded categorical variables using **Label Encoding** and **One-Hot Encoding**.  
- Handled imbalanced data (if any) through stratified sampling.  
- Scaled and cleaned data for efficient model input.

---

### 3. Model Building
- Split data into **training (80%)** and **testing (20%)** sets.  
- Chose evaluation metrics: **Accuracy**, **Precision**, **Recall**, and **F1-score**.  
- Implemented and trained:
  - **LightGBM Classifier**  
  - **XGBoost Classifier**

---

### 4. Hyperparameter Tuning
- Used **GridSearchCV** or **RandomizedSearchCV** to optimize key parameters such as:
  - Learning rate (`learning_rate`)
  - Number of estimators (`n_estimators`)
  - Maximum depth (`max_depth`)
  - Minimum child weight / leaf nodes  
- Compared performance improvements after tuning.

---

### 5. Comparative Analysis
| Metric | LightGBM | XGBoost |
|---------|-----------|----------|
| Accuracy | Higher / Lower (depends on results) |
| Precision | — |
| Recall | — |
| F1-score | — |

- Compared overall model performance visually and statistically.  
- Discussed differences in **speed**, **memory efficiency**, and **accuracy** between LightGBM and XGBoost.  
- Highlighted real-world scenarios where each algorithm performs best.

---

## ⚙️ Tech Stack
| Category | Tools Used |
|-----------|-------------|
| Programming Language | Python |
| Libraries | `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `lightgbm` |
| Algorithms | LightGBM, XGBoost |
| Environment | Jupyter Notebook / VS Code |

---

## 📈 Results & Insights
- **LightGBM** generally performed faster due to its leaf-wise growth strategy.  
- **XGBoost** showed robust performance with stable accuracy and fewer overfitting risks.  
- Both models provided high accuracy, but tuning parameters had significant influence.  
- Demonstrated the importance of **boosting algorithms** in handling complex, structured datasets.

---

## 📁 Repository Structure
