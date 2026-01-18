SAGE is a faculty-assisted AI early-warning and decision-support system designed to identify early academic risk and burnout indicators in university students.

The system analyzes academic performance, engagement behavior, and well-being signals to generate explainable risk alerts that support timely faculty intervention — with a strong emphasis on human-in-the-loop decision-making.

## 🎯 Project Objectives

- Identify students at **Low / Medium / High academic risk**
- Detect early burnout indicators using non-invasive data
- Provide interpretable and ethical predictions
- Support early intervention by educators and counselors

---
## 🏗️ System Perspective

SAGE is designed as a decision-support system rather than a standalone prediction model.

The system consists of:
- An intelligence layer for academic and burnout risk prediction
- A faculty alert layer that prioritizes students based on risk severity
- A human-in-the-loop intervention workflow to ensure ethical and responsible use

Faculty members remain central to all decisions, with AI serving as an assistive tool.

## 📊 Dataset Overview

student_id
week_number

avg_score
score_delta
score_variance
assignment_completion_rate
late_submission_count

attendance_rate
attendance_delta
lms_activity_index
participation_score
engagement_irregularity

stress_index
workload_pressure
sleep_irregularity_proxy
wellbeing_delta

rolling_avg_score_3w
attendance_trend_slope
engagement_drop_rate
stress_acceleration
risk_velocity

academic_risk_level
burnout_risk_score
alert_triggered

The SAGE dataset is a weekly, student-level time-series dataset designed to capture academic performance, engagement behavior, and well-being proxy signals. It emphasizes trend-based features and explainable indicators to enable early detection of academic risk and burnout while supporting human-in-the-loop faculty decision making.
---

## 🧠 Current Project Stage

✅ Dataset design and validation  
✅ Initial machine learning model (baseline)  
⬜ Time-based student risk tracking  
⬜ Faculty alert logic and intervention workflow  
⬜ Interactive faculty dashboard  
⬜ Explainable AI integration (SHAP)  

---

## 🛠️ Tech Stack

- Python
- Pandas
- Jupyter Notebook
- Scikit-learn 
- Streamlit

---

## 🚀 Getting Started

## 👤 Author

Dhara  
B.Tech Student | Aspiring Data Scientist  
