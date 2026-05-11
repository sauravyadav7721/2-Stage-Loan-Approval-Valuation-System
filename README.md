````md
# 💰 Two-Stage Loan Approval & Loan Amount Prediction System

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Loan%20Prediction-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.12-yellow?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Framework-Streamlit-red?style=for-the-badge&logo=streamlit" />
</p>

---

# 📌 Overview

This project is an **End-to-End Machine Learning Application** that uses a **Two-Stage Prediction System** for loan processing.

The application performs:

### ✅ Stage 1 — Loan Approval Prediction
Predicts whether a loan applicant should be:
- Approved
- Rejected

### ✅ Stage 2 — Loan Amount Prediction
If the applicant is approved, the system predicts:
- Estimated loan amount

This project demonstrates:
- Machine Learning workflows
- Classification & Regression models
- Model deployment using Streamlit
- End-to-End ML pipeline implementation

---

# 🚀 Features

- ✅ Two-stage ML pipeline
- ✅ Loan approval classification model
- ✅ Loan amount regression model
- ✅ Interactive Streamlit web application
- ✅ Config-based runtime management
- ✅ Modular project structure
- ✅ CLI support
- ✅ UV package management support

---

# 🧠 Machine Learning Workflow

## 🔹 Stage 1 — Classification Model

The first ML model predicts:
- Loan Approved → Yes
- Loan Approved → No

### Classification Problem
Possible algorithms:
- Logistic Regression
- Random Forest Classifier
- XGBoost
- Decision Tree

---

## 🔹 Stage 2 — Regression Model

If the applicant is approved, the second ML model predicts:
- Loan Amount

### Regression Problem
Possible algorithms:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

---

# 🛠️ Tech Stack

## 💻 Programming & Frameworks
- Python 3.12
- Streamlit

## 📊 Machine Learning Libraries
- Scikit-learn
- Pandas
- NumPy
- Joblib / Pickle

## ⚙️ Tools
- UV Package Manager
- Git & GitHub

---

# 📂 Project Structure

```bash
2-Stage-Loan-Approval-Valuation-System/
│
├── models/                     # Trained ML models
│   ├── stage_1_model.pkl
│   └── stage_2_model.pkl
│
├── streamlit_app.py            # Streamlit UI
├── main.py                     # CLI Application
├── config.yaml                 # Runtime configuration
├── requirements.txt            # Dependencies
├── README.md                   # Project Documentation
│
└── notebooks/                  # Jupyter notebooks (optional)
````

---

# ⚡ Quick Start (Local Setup)

## 1️⃣ Clone Repository

```bash
git clone https://github.com/sauravyadav7721/2-Stage-Loan-Approval-Valuation-System.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd 2-Stage-Loan-Approval-Valuation-System
```

---

## 3️⃣ Create Virtual Environment

```bash
uv venv
```

---

## 4️⃣ Install Dependencies

```bash
uv pip install -r requirements.txt
```

---

## 5️⃣ Add Trained Models

Place your trained model files inside:

```bash
models/
```

Example:

```bash
models/
├── stage_1_model.pkl
└── stage_2_model.pkl
```

---

# ▶️ Run the Application

## 🔹 Run Streamlit UI

```bash
uv run streamlit run streamlit_app.py
```

---

## 🔹 Run CLI Version

```bash
uv run python main.py
```

---

# ⚙️ Configuration

Runtime parameters and model paths are managed using:

```bash
config.yaml
```

Example:

* Model paths
* Runtime settings
* Feature configuration

---

# 📦 Managing Dependencies with UV

## Install Packages

```bash
uv pip install -r requirements.txt
```

## Freeze Installed Packages

```bash
uv pip freeze > requirements.txt
```

---

# 🔄 Git Instructions

```bash
git init
git add .
git commit -m "Initial Commit"

git remote add origin https://github.com/sauravyadav7721/2-Stage-Loan-Approval-Valuation-System.git

git pull origin main --allow-unrelated-histories

git push -u origin main
```

---

# ⚠️ Important Notes

* Ensure the same Python and library versions are used during:

  * Model training
  * Model deployment

* Python Version Used:

```bash
Python 3.12
```

* Place trained `.pkl` files correctly inside the `models/` folder.

---

# 📊 Future Improvements

* ✅ Model deployment on cloud
* ✅ Docker containerization
* ✅ CI/CD pipeline
* ✅ MLOps integration
* ✅ Explainable AI (XAI)
* ✅ Loan risk analytics dashboard

---

# 🎯 Learning Outcomes

This project demonstrates understanding of:

* Machine Learning Pipelines
* Classification & Regression
* Model Deployment
* Streamlit Applications
* Configuration Management
* End-to-End ML Systems

---

# 🔗 Repository Link

## GitHub Repository

https://github.com/sauravyadav7721/2-Stage-Loan-Approval-Valuation-System


# 👨‍💻 Author

## Saurav Yadav

Data Science Student | ML & AI Enthusiast

* GitHub: https://github.com/sauravyadav7721
* LinkedIn: https://www.linkedin.com/in/sauravyadav7721/

---

<p align="center">
  ⭐ If you found this project useful, consider giving it a star!
</p>
```
