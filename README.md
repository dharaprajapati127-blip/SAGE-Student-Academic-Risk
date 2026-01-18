# SAGE – Student Academic Growth & Early-Risk Intelligence System

SAGE is an AI-driven early warning system designed to identify **academic risk and burnout indicators** in university students before visible failure occurs.

The project focuses on detecting **silent strugglers** by analyzing a combination of academic performance, engagement behavior, and well-being signals.

---

## 🎯 Project Objectives

- Identify students at **Low / Medium / High academic risk**
- Detect early burnout indicators using non-invasive data
- Provide interpretable and ethical predictions
- Support early intervention by educators and counselors

---

## 📊 Dataset Overview

Each row represents a student record with the following features:

- Attendance percentage
- Internal assessment marks
- Assignment submission delay
- Weekly study hours
- Self-reported stress level (1–5)
- Self-reported sleep quality (1–5)

The dataset is currently **synthetic and simulated** to model realistic academic patterns while preserving privacy.

---

## 🧠 Current Project Stage

✅ Dataset design and validation  
✅ Initial data loading using Pandas  
⬜ Feature engineering  
⬜ Machine learning model development  
⬜ Explainability (SHAP)  
⬜ Interactive dashboard  

---

## 🛠️ Tech Stack

- Python
- Pandas
- Jupyter Notebook
- Scikit-learn (planned)
- Streamlit (planned)

---

## 🚀 Getting Started



df = pd.read_csv("student_risk_data.csv")
df
