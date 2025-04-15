# XAI-Sec-IoT: Explainable AI for Smart IoT Security Decisions 🧠🔐

This project introduces an explainable AI (XAI) framework for anomaly detection in smart city IoT sensor environments. It combines unsupervised machine learning with SHAP-based model explainability to enhance transparency in security decisions, aligning with the human-centered AI paradigm.

---

## 🌐 Overview

With the increasing deployment of IoT devices in critical infrastructures, ensuring reliable and interpretable security systems is essential. This project simulates realistic sensor logs, detects anomalies using Isolation Forest, and explains each decision with SHAP to empower system operators and decision makers with understandable insights.

---

## ✅ Key Features

- 🔁 Synthetic sensor data generation (temperature, humidity, motion)
- 🧪 Anomaly labeling via domain specific rules
- 🌲 Unsupervised anomaly detection using Isolation Forest
- 🔍 Explainable AI integration with SHAP
- 📊 Summary and individual decision visualizations
- 📁 Clean project structure for research portfolios and academic use

---

## 📊 Dataset Description

| Column         | Description                                |
|----------------|--------------------------------------------|
| `timestamp`    | Time log of the sensor reading             |
| `sensor_id`    | Unique identifier for each sensor          |
| `temperature`  | Recorded temperature (°C)                  |
| `humidity`     | Recorded humidity level (%)                |
| `motion`       | Motion detected (0 = no, 1 = yes)          |
| `anomaly_flag` | Labeled anomaly (based on defined rules)   |
| `anomaly_pred` | Model-predicted anomaly (0 = normal, 1 = anomaly) |

---

## 🧠 Tech Stack

- Python 3.8+
- Pandas, NumPy
- Scikit-learn (Isolation Forest)
- SHAP (TreeExplainer)
- Matplotlib

---

## 📈 Example Outputs

### 🔹 SHAP Summary Plot  
Shows which features (e.g., temperature, humidity, motion) had the greatest influence on the model’s anomaly predictions across the dataset.  
Used to assess global feature importance.

### 🔹 SHAP Waterfall Plot  
Explains how each feature contributed to a single anomaly prediction.  
Used to understand the reasoning behind one specific decision made by the model.


---


## 👩‍💻 Author

**Dicle Ceylan**
B.Sc. in Statistics, Yildiz Technical University (Class of 2026)  
Interested in AI, Cybersecurity, and IoT Security  
🌐 GitHub: github.com/DicleCeylann 
💼 LinkedIn: linkedin.com/in/dicle-ceylan


---

📄 License & Usage

This project is open source and can be freely used for academic, educational, or research purposes. If you build upon this work, please credit the repository.
