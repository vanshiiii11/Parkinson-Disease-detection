# Parkinson's Disease Prediction using Machine Learning and Explainable AI

This project focuses on the prediction of Parkinson's Disease using biomedical voice features. It implements supervised machine learning algorithms (Random Forest, SVM) alongside Explainable AI (XAI) tools such as SHAP and LIME to ensure transparency and interpretability in healthcare diagnostics.

---

## 🎯 Objective

Develop a robust machine learning pipeline capable of predicting Parkinson's Disease from voice recordings, while offering explainability for end-users and medical professionals.

---

## 🧰 Technologies & Tools

- **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **ML Models:** Random Forest Classifier, Support Vector Machine (SVM)  
- **Explainability:** SHAP (SHapley Additive exPlanations), LIME  
- **Development Tools:** Jupyter Notebook, VS Code

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Normalization & feature scaling
   - Exploratory Data Analysis
   - Train-Test Split

2. **Model Training**
   - Random Forest
   - SVM (with hyperparameter tuning)

3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix, ROC-AUC

4. **Model Explainability**
   - SHAP for global and instance-level feature importance
   - LIME for local prediction interpretation

---

## 📊 Results

- Achieved high predictive performance with Random Forest.
- SHAP visualizations highlighted key voice-based biomarkers.
- LIME confirmed model stability on diverse patient samples.

---

## 🔍 Explainable AI (XAI)

Given the critical nature of healthcare applications, we integrated XAI techniques:
- **SHAP:** Quantifies the impact of each feature on the model’s prediction.
- **LIME:** Explains individual predictions by approximating the model locally.

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/tanishhhk/parkinsons-disease-prediction-voice-xai.git
   cd parkinsons-disease-prediction-voice-xai

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Run the Notebook:
   ```bash
   jupyter notebook Parkinson_Disease_Prediction.ipynb

# 👤 Author

## Tanishk Jain

### Connect with me

- **GitHub:** [tanishhhk](https://github.com/tanishhhk)
- **LinkedIn:** [linkedin.com/in/tanishhhk](https://linkedin.com/in/tanishhhk)

---

# Acknowledgements

This project was originally developed in collaboration with [Soham Saoji](https://github.com/SohamSaoji).  
The version hosted on this repository is a refined, restructured, and documented version to showcase my independent work and learning outcomes in machine learning and XAI.

Gratitude to open-source contributors and the creators of SHAP and LIME libraries, whose tools were instrumental in building interpretable AI systems for this project.

---
