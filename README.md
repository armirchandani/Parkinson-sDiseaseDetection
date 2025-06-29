# ParkinsonsDiseaseDetection

🧠 **Parkinson’s Disease Detection using Machine Learning**
This project applies machine learning techniques to analyze biomedical voice measurements and classify whether a patient has Parkinson’s Disease (PD). The dataset contains various voice features, such as fundamental frequency, jitter, shimmer, and nonlinear dynamical complexity measures.

📁 **Dataset**
Source: UCI Machine Learning Repository

Records: 195

Features: 22 numerical features (including NHR, HNR, RPDE, DFA, spread1, spread2, D2, PPE)

Target: Binary label indicating Parkinson’s diagnosis (status: 1 = PD, 0 = healthy)

📊 **Features Used**
Nonlinear measures: RPDE, DFA, D2, PPE

Frequency and noise-based measures: NHR, HNR, spread1, spread2

These features are correlated with vocal irregularities commonly found in Parkinson’s patients.

🔧 **Tools & Libraries**
Python, NumPy, pandas, scikit-learn, matplotlib, seaborn

🧪 **Model Pipeline**
Preprocessing: StandardScaler, missing value checks

Feature Selection: Correlation analysis & PCA (optional)

Models: Logistic Regression, Random Forest, SVM, KNN

Evaluation Metrics: Accuracy, F1 Score, Confusion Matrix, ROC-AUC

✅ **Results**
Achieved ~90% accuracy using SVM with RBF kernel

Identified PPE, D2, and spread1 as key predictive features

📌 **Key Takeaways**
This project demonstrates the ability of machine learning algorithms to aid in the early detection of Parkinson’s Disease using voice-based features. It showcases data preprocessing, feature engineering, classification, and interpretability of biomedical signals.


