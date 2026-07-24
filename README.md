# 🧠 Parkinson's Disease Detection Using Machine Learning

A machine learning project that predicts whether a patient has **Parkinson's Disease (PD)** using biomedical voice measurements. By analyzing vocal characteristics such as frequency, jitter, shimmer, and nonlinear complexity measures, the model identifies patterns associated with Parkinson's Disease to support early diagnosis.

This project demonstrates the complete machine learning workflow, including data preprocessing, feature analysis, model training, evaluation, and interpretation.

---

## Table of Contents

1. Features
2. How It Works
3. Why It Matters
4. Tech Stack
5. Installation
6. Usage
7. Project Structure
8. Results
9. Future Improvements
10. Contributors

---

# Features

- **Data Preprocessing**
  - Checked for missing values and cleaned the dataset
  - Standardized numerical features using **StandardScaler**
  - Prepared biomedical voice measurements for model training

- **Feature Analysis**
  - Explored correlations between voice characteristics and Parkinson's diagnosis
  - Performed feature selection using correlation analysis
  - Applied Principal Component Analysis (PCA) for dimensionality reduction (optional)

- **Machine Learning Models**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Random Forest
  - K-Nearest Neighbors (KNN)

- **Model Evaluation**
  - Compared multiple classification models
  - Evaluated performance using Accuracy, F1-Score, Confusion Matrix, and ROC-AUC
  - Identified the best-performing model for disease prediction

---

# How It Works

1. **Load Dataset**
   - Import biomedical voice measurements from the Parkinson's Disease dataset.

2. **Preprocess Data**
   - Handle missing values
   - Standardize numerical features
   - Explore feature relationships

3. **Train Machine Learning Models**
   - Train Logistic Regression, Random Forest, KNN, and SVM classifiers.

4. **Evaluate Performance**
   - Compare model accuracy and classification metrics.
   - Visualize results using confusion matrices and ROC curves.

5. **Interpret Results**
   - Identify the most influential voice features for Parkinson's detection.

---

# Why It Matters

Parkinson's Disease is a progressive neurological disorder where early diagnosis can improve treatment and patient outcomes.

This project demonstrates how machine learning can:

- Support early disease detection
- Analyze complex biomedical signals
- Improve diagnostic decision-making
- Assist healthcare professionals with data-driven insights
- Showcase practical applications of AI in healthcare

---

# Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Machine Learning

- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)
- Principal Component Analysis (PCA)

### Development Tools

- Jupyter Notebook
- Git
- GitHub

---

# Installation

Clone the repository

```bash
git clone https://github.com/armirchandani/ParkinsonsDiseaseDetection.git
cd ParkinsonsDiseaseDetection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook ParkinsonsDiseaseDetection.ipynb
```

---

# Usage

### Load the Dataset

```python
import pandas as pd

df = pd.read_csv("parkinsons.csv")
```

### Train the SVM Model

```python
from sklearn.svm import SVC

model = SVC(kernel="rbf")
model.fit(X_train, y_train)
```

### Predict Parkinson's Disease

```python
prediction = model.predict(new_patient_data)
```

---

# Project Structure

```
ParkinsonsDiseaseDetection/
│
├── parkinsons.csv
├── ParkinsonsDiseaseDetection.ipynb
├── requirements.txt
└── README.md
```

---

# Results

🧠 Achieved approximately **90% classification accuracy** using an **SVM with an RBF kernel**

📊 Compared the performance of **Logistic Regression, Random Forest, KNN, and SVM**

🔍 Identified **PPE, D2, and spread1** as the most predictive voice features

📈 Demonstrated the effectiveness of machine learning for early Parkinson's Disease detection using biomedical voice measurements

---

# Future Improvements

- Perform hyperparameter tuning using GridSearchCV
- Explore ensemble learning methods such as XGBoost and LightGBM
- Apply cross-validation to improve model robustness
- Build a Streamlit web application for real-time disease prediction
- Investigate deep learning models for biomedical signal classification

---

# Contributors

**Aastha Mirchandani**

Business Analytics Student | University of San Francisco

Interested in Machine Learning, Healthcare Analytics, Data Science, and Artificial Intelligence

---

⭐ If you found this project helpful, consider giving it a star!
