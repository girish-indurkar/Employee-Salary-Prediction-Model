# 💼 Employee Salary Classification App

A machine learning project that predicts whether an employee earns **more than 50K** or **50K or less** based on features like age, education, occupation, hours per week, and more.

> Built using **Logistic Regression** and **Random Forest**, deployed via **Streamlit** and **Gradio**, and trained in **Google Colab**.

---

## 🔍 Problem Statement

The goal is to classify whether an employee earns more than 50K per year using census-style data.

### Features used:
- Age
- Education
- Occupation
- Gender
- Hours per Week
- Capital Gain / Loss
- Other categorical & numerical features

---

## 🛠️ Tools & Technologies
- 🧠 **Machine Learning Models**: Logistic Regression, Random Forest
- 📊 **Libraries**: Pandas, Scikit-learn, Joblib
- 🎛 **UI Interfaces**: Streamlit & Gradio
- ☁️ **Notebook**: Google Colab
- 🚀 **Deployment**: Streamlit Cloud / Hugging Face Spaces *(optional)*

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




