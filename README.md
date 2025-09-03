
# 🕵️ Fraud Detection

A Machine Learning project for detecting fraudulent transactions using supervised learning techniques.  
The goal of this repository is to build, train, and evaluate models that can identify potential fraud in financial transaction datasets with high accuracy.

---

## 🚀 Features
- Preprocessing of transactional datasets (handling missing values, scaling, encoding).
- Exploratory Data Analysis (EDA) with visualizations.
- Multiple ML models implemented:
  - Logistic Regression
  - Random Forest
  - Decision Tree
  - k-Nearest Neighbors (kNN)
  - Ensemble Methods
- Model evaluation with metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Easily extendable to include Deep Learning models.

---

## 🛠️ Tech Stack
- **Programming Language:** Python 3.x  
- **Libraries:**  
  - pandas, numpy, matplotlib, seaborn  
  - scikit-learn  
  - imbalanced-learn (SMOTE, resampling)  
  - Jupyter Notebook  

---

## 📂 Project Structure
fraud-detection/
│-- data/                # Dataset folder (not uploaded due to size)
│-- notebooks/           # Jupyter notebooks for EDA & model training
│-- src/                 # Python scripts for preprocessing & models
│-- results/             # Saved model outputs and evaluation metrics
│-- requirements.txt     # Dependencies
│-- README.md            # Project documentation

---

## ⚙️ Installation
1. Clone the repository:
   git clone https://github.com/arry-codes/fraud-detection.git
   cd fraud-detection

2. Create and activate a virtual environment (recommended):
   python -m venv venv
   source venv/bin/activate   # On Linux/Mac
   venv\Scripts\activate      # On Windows

3. Install dependencies:
   pip install -r requirements.txt

---

## ▶️ Usage
Run the preprocessing and training pipeline:
   python src/train_model.py

Or open the Jupyter notebooks for step-by-step execution:
   jupyter notebook notebooks/

---

## 📊 Evaluation
Example metrics (using Random Forest):
- Accuracy: 98%
- Precision: 97%
- Recall: 95%
- F1-Score: 96%
- ROC-AUC: 0.99

(These values may vary depending on dataset split & parameters.)

---





<img width="1440" height="900" alt="Screenshot 2025-07-21 at 7 55 30 PM" src="https://github.com/user-attachments/assets/db8f538e-3829-4d78-9109-4a0238961425" />
