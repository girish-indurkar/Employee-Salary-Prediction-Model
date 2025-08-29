# 💼 Employee Salary Classification App  

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo.svg" alt="scikit-learn" width="120"/>
  <img src="https://pandas.pydata.org/static/img/pandas.svg" alt="pandas" width="120"/>
  <img src="https://streamlit.io/images/brand/streamlit-mark-color.png" alt="streamlit" width="120"/>
  <img src="https://www.python.org/static/community_logos/python-logo.png" alt="python" width="140"/>
</p>

---

## 📌 Overview  
This project is a **Machine Learning Web App** built with **Scikit-learn, Pandas, Streamlit, and Pyngrok** that predicts whether an employee earns **>50K** or **≤50K** based on their details (age, education, occupation, hours per week, experience).  

It compares two models:  
- ⚖️ **Logistic Regression**  
- 🌲 **Random Forest Classifier**  

The best model is automatically selected and deployed in a **Streamlit app** accessible through **Ngrok**.

---

## 🚀 Features  
✅ Data preprocessing (handling missing values, label encoding)  
✅ Model training & accuracy comparison  
✅ Interactive **Streamlit UI** for single predictions  
✅ **Batch predictions** via CSV upload  
✅ Export & load trained model (`.pkl` format)  
✅ Shareable **Ngrok public URL** for deployment  

---

## 🛠️ Tech Stack  

- 🐍 **Python 3**  
- 📊 **Pandas, Matplotlib**  
- 🤖 **Scikit-learn**  
- 🎨 **Streamlit**  
- 🌐 **Ngrok (via pyngrok)**  

---

## 📂 Project Structure  

```
├── app.py               # Streamlit web app
├── adult 3.csv          # Dataset
├── model.pkl            # Saved best model
├── encoders.pkl         # Saved label encoders
├── streamlit_log.txt    # Streamlit logs
├── README.md            # Project documentation
```

---

## ⚙️ Installation  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/yourusername/employee-salary-classification.git
cd employee-salary-classification
```

2️⃣ Install dependencies:  
```bash
pip install scikit-learn pandas matplotlib streamlit gradio colabcode pyngrok joblib
```

3️⃣ Run the Streamlit app with Ngrok:  
```bash
streamlit run app.py
```

4️⃣ Expose to the web using Ngrok (inside Python script or separately):  
```python
from pyngrok import ngrok
ngrok.set_auth_token("YOUR_AUTH_TOKEN")
public_url = ngrok.connect("http://localhost:8501")
print("Streamlit App URL:", public_url)
```

---

## 🖥️ Usage  

### 🔍 Single Prediction  
- Enter **age, education, occupation, working hours, and experience** in the sidebar.  
- Click **Predict Salary Class** to see the result.  

### 📁 Batch Prediction  
- Upload a **CSV file** with employee details.  
- The app predicts salaries for all employees and allows downloading results.  

---

## 📊 Model Accuracy Comparison  

The script compares **Logistic Regression** and **Random Forest**:  

![Accuracy Comparison](https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.png) <!-- Replace with your actual accuracy graph -->

---

## 🌎 Deployment  

This project uses **Ngrok** to deploy the app on a public URL.  

Example:  
```text
Streamlit App URL: http://xxxxx.ngrok.io
```

---

## 📜 License  
This project is licensed under the **MIT License**.  

---

<p align="center">
  Made with ❤️ using <b>Python & Streamlit</b>  
</p>
