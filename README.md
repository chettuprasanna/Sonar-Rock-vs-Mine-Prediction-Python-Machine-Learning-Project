# Sonar Rock vs Mine Classification  
A Machine Learning project that classifies sonar signals as **Rock (R)** or **Mine (M)** using multiple ML models and ensemble techniques.  
This project uses the **Sonar Dataset from UCI Machine Learning Repository**, which contains 60 frequency-based features extracted from sonar signals.

---

## 📌 Project Objective
To build and compare multiple machine learning models that predict whether a sonar signal has bounced off **a metal mine** or **a naturally occurring rock**.

---

## 📂 Dataset Information
- **Dataset Name:** Sonar Mines vs Rocks  
- **Samples:** 208  
- **Features:** 60 numerical sonar frequencies  
- **Target Labels:**  
  - **R** → Rock  
  - **M** → Mine  

Each feature represents the energy reflected at a particular sonar frequency.

---

## 🧠 Machine Learning Workflow

### 1. **Data Preprocessing**
- Loaded dataset using pandas  
- Separated features (X) and target (y)  
- Label Encoded target values (R → 0, M → 1)  
- Train-test split (80% training, 20% testing)  
- Standardization (where required)

---

### 2. **Models Trained**
This project includes the training of **multiple ML models**, including:

- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Naive Bayes  
- AdaBoost  
- Bagging Classifier  
- Gradient Boosting  
- XGBoost  
- Voting Classifier (Ensemble)

All models were trained, tested, and evaluated on the same dataset for fair comparison.

---

## 📊 Evaluation Metrics
For each model, the following metrics were generated:

- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)

A final **comparison table** summarizing all model accuracies is included in the notebook.

---

## 📈 Visualizations
The project includes:
- Confusion matrices for every model  
- PCA 2D Scatter Plot  
- Final accuracy comparison  
- Ensemble model comparison  

---

## 📁 Project Structure
📦 Sonar-Classification-Project
├── sonar.csv
├── Sonar_Classification.ipynb
├── README.md
└── results/
├── confusion_matrices/
├── accuracy_table.csv
└── pca_plot.png
