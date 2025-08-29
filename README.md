# 💼 Employee Salary Prediction App


<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.9+-blue?logo=python&logoColor=white" alt="Python"></a>
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/Scikit--Learn-1.3.0-orange?logo=scikitlearn&logoColor=white" alt="scikit-learn"></a>
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-2.0.3-purple?logo=pandas&logoColor=white" alt="pandas"></a>
  <a href="https://streamlit.io/"><img src="https://img.shields.io/badge/Streamlit-1.25.0-ff4b4b?logo=streamlit&logoColor=white" alt="streamlit"></a>
  <a href="https://ngrok.com/"><img src="https://img.shields.io/badge/Ngrok-deploy-1e77ff?logo=ngrok&logoColor=white" alt="ngrok"></a>
</p>


This project predicts whether an employee earns **>50K or <=50K** based on input features like age, education, occupation, etc.
A machine learning project that predicts whether an employee earns **more than 50K** or **50K or less** based on features like age, education, occupation, hours per week, and more.

## 🔧 Features
> Built using **Logistic Regression** and **Random Forest**, deployed via **Streamlit** and **Gradio**, and trained in **Google Colab**.

- ✅ Interactive Streamlit Web App
- ✅ Batch prediction using CSV
- ✅ Gradio interface (optional)
- ✅ Trained model using Random Forest / Logistic Regression
---

## 🧠 Model Details
## 🔍 Problem Statement

Trained on UCI Adult Income Dataset using scikit-learn and joblib for model saving.
The goal is to classify whether an employee earns more than 50K per year using census-style data.

## 📂 Files
### Features used:
- Age
- Education
- Occupation
- Gender
- Hours per Week
- Capital Gain / Loss
- Other categorical & numerical features

| File Name         | Description |
|------------------|-------------|
| `app.py`         | Streamlit app for interactive UI |
| `model_gradio.py`| Gradio interface (optional) |
| `best_model.pkl` | Saved ML model |
| `salary_model.ipynb` | Full Colab notebook for training + deployment |
| `sample_input.csv` | Sample CSV for batch predictions |
---

## 🚀 Run App Locally (Streamlit)
## 🛠️ Tools & Technologies
- 🧠 **Machine Learning Models**: Logistic Regression, Random Forest
- 📊 **Libraries**: Pandas, Scikit-learn, Joblib
- 🎛 **UI Interfaces**: Streamlit & Gradio
- ☁️ **Notebook**: Google Colab
- 🚀 **Deployment**: Streamlit Cloud / Hugging Face Spaces *(optional)*

```bash
pip install streamlit pandas scikit-learn joblib```
---

## 📈 Model Performance

| Model               | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| Logistic Regression| 83%      | 0.79      | 0.75   |
| Random Forest      | 87% ✅   | 0.85      | 0.81   |

*(Random Forest performed better and was used in the final app)*

---

## 💡 How it Works

### Streamlit App Demo
- Input single employee details via sidebar
- Predict salary class instantly
- Option to upload CSV file for **batch prediction**

### Gradio App Demo
- Simple web UI for quick single prediction
- User-friendly and responsive

---

## 📁 Project Structure:

├── app.py                # Streamlit frontend  
├── gradio_app.py         # Gradio interface  
├── best_model.pkl        # Trained Random Forest model  
├── employee_data.csv     # Input dataset  
├── salary_predictor.ipynb# Main ML training notebook  
├── requirements.txt      # Python dependencies  


---

## 🚀 How to Run

### ✅ Option 1: Run on Google Colab

Upload files and run the following command:

```python
!streamlit run app.py

Option 2: Run Locally (Requires Python)
1.Clone the repository:
git clone https://github.com/girish-indurkar/Employee-Salary-Prediction-Model.git
cd Employee-Salary-Prediction-Model
```
2.Install dependencies:
```
pip install -r requirements.txt
```

3.Run the Streamlit app:
```
streamlit run app.py
```




This project predicts whether an employee earns **>50K or <=50K** based on input features like age, education, occupation, etc.
A machine learning project that predicts whether an employee earns **more than 50K** or **50K or less** based on features like age, education, occupation, hours per week, and more.

## 🔧 Features
> Built using **Logistic Regression** and **Random Forest**, deployed via **Streamlit** and **Gradio**, and trained in **Google Colab**.

- ✅ Interactive Streamlit Web App
- ✅ Batch prediction using CSV
- ✅ Gradio interface (optional)
- ✅ Trained model using Random Forest / Logistic Regression
---

## 🧠 Model Details
## 🔍 Problem Statement

Trained on UCI Adult Income Dataset using scikit-learn and joblib for model saving.
The goal is to classify whether an employee earns more than 50K per year using census-style data.

## 📂 Files
### Features used:
- Age
- Education
- Occupation
- Gender
- Hours per Week
- Capital Gain / Loss
- Other categorical & numerical features

| File Name         | Description |
|------------------|-------------|
| `app.py`         | Streamlit app for interactive UI |
| `model_gradio.py`| Gradio interface (optional) |
| `best_model.pkl` | Saved ML model |
| `salary_model.ipynb` | Full Colab notebook for training + deployment |
| `sample_input.csv` | Sample CSV for batch predictions |
---

## 🚀 Run App Locally (Streamlit)
## 🛠️ Tools & Technologies
- 🧠 **Machine Learning Models**: Logistic Regression, Random Forest
- 📊 **Libraries**: Pandas, Scikit-learn, Joblib
- 🎛 **UI Interfaces**: Streamlit & Gradio
- ☁️ **Notebook**: Google Colab
- 🚀 **Deployment**: Streamlit Cloud / Hugging Face Spaces *(optional)*

```bash
pip install streamlit pandas scikit-learn joblib
---

## 📈 Model Performance

| Model               | Accuracy | Precision | Recall |
|--------------------|----------|-----------|--------|
| Logistic Regression| 83%      | 0.79      | 0.75   |
| Random Forest      | 87% ✅   | 0.85      | 0.81   |

*(Random Forest performed better and was used in the final app)*

---

## 💡 How it Works

### Streamlit App Demo
- Input single employee details via sidebar
- Predict salary class instantly
- Option to upload CSV file for **batch prediction**

### Gradio App Demo
- Simple web UI for quick single prediction
- User-friendly and responsive

---

## 📁 Project Structure:

├── app.py                # Streamlit frontend  
├── gradio_app.py         # Gradio interface  
├── best_model.pkl        # Trained Random Forest model  
├── employee_data.csv     # Input dataset  
├── salary_predictor.ipynb# Main ML training notebook  
├── requirements.txt      # Python dependencies  


---

## 🚀 How to Run

### ✅ Option 1: Run on Google Colab

Upload files and run the following command:

```python
!streamlit run app.py

Option 2: Run Locally (Requires Python)
1.Clone the repository:
git clone https://github.com/girish-indurkar/Employee-Salary-Prediction-Model.git
cd Employee-Salary-Prediction-Model

2.Install dependencies:
pip install -r requirements.txt

3.Run the Streamlit app:
streamlit run app.py



