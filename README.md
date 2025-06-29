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

📌 **Resume Bullet Points**
Project Title: Parkinson's Disease Detection Using Voice-Based Features
Tools: Python, scikit-learn, pandas, matplotlib, seaborn

Developed a machine learning pipeline to classify Parkinson’s disease based on biomedical voice measurements, achieving 90%+ accuracy using Support Vector Machines.

Engineered and analyzed features such as Harmonics-to-Noise Ratio, Nonlinear Dynamics (D2, RPDE, PPE) to detect motor disorders through voice patterns.

Implemented preprocessing steps including standardization, outlier handling, and feature correlation to optimize model performance.

Evaluated multiple models (Logistic Regression, Random Forest, KNN, SVM), tuning hyperparameters using GridSearchCV for optimal accuracy and interpretability.

Visualized feature importance and confusion matrices to explain classification decisions to both technical and non-technical stakeholders.

Demonstrated impact of voice signal analysis in healthcare AI applications, aligning data science skills with real-world biomedical problems.
