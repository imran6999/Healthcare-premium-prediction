# Healthcare-premium-prediction
Healthcare premium prediction project (Regression)

# 🏥 Health Insurance Premium Predictor
A machine learning-powered web application built with **Streamlit** that predicts healthcare insurance premium costs based on user profile inputs such as age, BMI category, medical history, and more.

## 🚀 Features
- 🎯 Predict insurance premium using trained ML models.
- 📊 Dynamic form inputs for real-time prediction.
- 👤 Personalized based on:
  - Age
  - Income
  - Smoking habits
  - BMI category
  - Medical history
  - Region, etc.
- 🔁 Automatically chooses the appropriate model (`young` or `rest`) based on user age.
- 🧪 Preprocessing includes one-hot encoding, normalization, and scaling.

---

## 🧠 Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Backend/ML**:
  - `scikit-learn`
  - `joblib`
  - `pandas`
  - `numpy`
- **Model Training**: (not included here, assumed pre-trained)
- **Deployment**: Streamlit Cloud / Localhost

---

## 📁 Project Structure

```bash
Healthcare-premium-prediction/
├── artifacts/
│   ├── model_young.joblib
│   ├── model_rest.joblib
│   ├── scaler_young.joblib
│   └── scaler_rest.joblib
├── app.py                # Streamlit app interface
├── utils.py              # Preprocessing and prediction logic
├── requirements.txt
└── README.md


Try the live demo 👉 [Streamlit Cloud Link](https://healthcare-premium-prediction-apps.streamlit.app/)

