# Credit Risk Modelling

This project focuses on building a robust machine learning pipeline to predict credit risk using real-world financial datasets from Bank of Baroda and CIBIL. The workflow includes data preprocessing, feature selection, model development, hyperparameter tuning with Optuna, and experiment tracking using MLflow.

---

## 📅 Project Duration

**May 2024 – June 2024**

---

## 🎯 Objective

To predict the likelihood of a borrower defaulting on a loan using financial and credit history data. This helps financial institutions minimize lending risk and make data-driven decisions.

---

## ✅ Features

- **📊 Data Preprocessing**
  - Cleaned and merged datasets from **Bank of Baroda** and **CIBIL** using inner joins
  - Domain-specific strategies applied to handle missing values effectively

- **📈 Feature Selection**
  - Applied statistical techniques including:
    - Chi-square test
    - ANOVA
    - Variance Inflation Factor (VIF)
  - Improved model accuracy by 15% by reducing multicollinearity and irrelevant features

- **🧠 Model Development**
  - Built classification models:
    - Random Forest
    - XGBoost
  - Achieved an accuracy of **82%**

- **🔧 Hyperparameter Tuning**
  - Used **Optuna** for efficient and automated hyperparameter optimization

- **📊 Experiment Tracking**
  - All experiments and metrics logged using **MLflow**

---

## 🧰 Tech Stack

| Component               | Tools/Libraries                  |
|-------------------------|----------------------------------|
| Language                | Python                          |
| Data Handling           | Pandas                          |
| Feature Selection       | Scikit-learn, SciPy             |
| Modeling                | Random Forest, XGBoost          |
| Hyperparameter Tuning   | Optuna                          |
| Experiment Tracking     | MLflow                          |

---

## 📁 Project Structure

credit-risk-modelling/
├── data/
│ ├── bob_data.csv
│ └── cibil_data.csv
├── preprocessing/
│ └── data_cleaning.py
├── feature_selection/
│ └── feature_selection.py
├── models/
│ ├── random_forest.py
│ └── xgboost_model.py
├── tuning/
│ └── optuna_tuner.py
├── tracking/
│ └── mlflow_logger.py
├── main.py
├── requirements.txt
└── README.md

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository


```bash

git clone https://github.com/your-username/credit-risk-modelling.git
cd credit-risk-modelling
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Add Your Datasets
Place your bob_data.csv and cibil_data.csv files in the data/ folder.

4. Run the Pipeline
bash
Copy
Edit
python main.py
This will trigger data preprocessing, feature selection, model training, tuning, and MLflow tracking.


Evaluation Metrics
Accuracy

Precision

Recall

F1 Score

ROC-AUC Curve



| Model         | Accuracy | F1 Score | Tuned with |
| ------------- | -------- | -------- | ---------- |
| Random Forest | 80%      | 0.78     | Optuna     |
| XGBoost       | 82%      | 0.81     | Optuna     |


