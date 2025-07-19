# 💼 Employee Salary Prediction App

This project predicts whether an employee earns **>50K or <=50K** based on input features like age, education, occupation, etc.

## 🔧 Features

- ✅ Interactive Streamlit Web App
- ✅ Batch prediction using CSV
- ✅ Gradio interface (optional)
- ✅ Trained model using Random Forest / Logistic Regression

## 🧠 Model Details

Trained on UCI Adult Income Dataset using scikit-learn and joblib for model saving.

## 📂 Files

| File Name         | Description |
|------------------|-------------|
| `app.py`         | Streamlit app for interactive UI |
| `model_gradio.py`| Gradio interface (optional) |
| `best_model.pkl` | Saved ML model |
| `salary_model.ipynb` | Full Colab notebook for training + deployment |
| `sample_input.csv` | Sample CSV for batch predictions |

## 🚀 Run App Locally (Streamlit)

```bash
pip install streamlit pandas scikit-learn joblib
streamlit run app.py
