<div align="center">

# 🛡️ Intelligent Network Intrusion Detection System
### End-to-End Machine Learning Pipeline using CIC-IDS2017

<img src="https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python"/>
<img src="https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikit-learn"/>
<img src="https://img.shields.io/badge/XGBoost-Gradient%20Boosting-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/LightGBM-Boosting-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/CatBoost-Boosting-yellow?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>

### 🚀 Research-Oriented Cybersecurity Machine Learning Project

---

**Author**

**Ali Kaisar Saiful**

Department of Computer Science & Engineering

State University of Bangladesh

</div>

---

# 📖 Project Overview

Cyber attacks continue to evolve rapidly, making traditional signature-based detection systems increasingly insufficient against modern threats. This project develops an **Intelligent Network Intrusion Detection System (IDS)** using Machine Learning techniques capable of distinguishing **Benign** and **Malicious** network traffic from real-world network flow data.

Unlike a conventional ML notebook focused solely on prediction accuracy, this project implements a **complete research-oriented workflow**, following modern machine learning engineering practices from raw data preprocessing to explainable AI.

The project is built on the **CIC-IDS2017** benchmark dataset developed by the **Canadian Institute for Cybersecurity (CIC)**, one of the most widely used datasets in intrusion detection research.

---

# 🎯 Objectives

- Build a robust binary Intrusion Detection System
- Compare multiple Machine Learning algorithms
- Develop a leak-free preprocessing pipeline
- Perform comprehensive Exploratory Data Analysis (EDA)
- Analyze feature relevance using Mutual Information
- Optimize models using Grid Search
- Evaluate models using Cross Validation
- Interpret predictions through Explainable AI (SHAP)
- Create a scalable workflow suitable for larger cybersecurity datasets

---

# 📂 Dataset

**Dataset**

CIC-IDS2017 (Friday Working Hours)

The dataset contains realistic network traffic consisting of both **Benign** and **Attack** flows collected in a controlled enterprise environment.

The project utilizes the combined Friday traffic:

- Friday Working Hours Morning
- Friday Working Hours Afternoon PortScan
- Friday Working Hours Afternoon DDoS

Resulting dataset:

- **~701,000 Network Flows**
- **79 Features**
- **Binary Classification**
  - Benign
  - Attack

---

# 🧠 Machine Learning Workflow

```
Raw CSV Files
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Analysis
(Mutual Information)
        │
        ▼
Train-Test Split
        │
        ▼
Leak-Free Preprocessing Pipeline
        │
        ▼
Model Training
        │
        ▼
Cross Validation
        │
        ▼
Hyperparameter Optimization
        │
        ▼
Performance Evaluation
        │
        ▼
ROC Analysis
        │
        ▼
Feature Importance
        │
        ▼
SHAP Explainability
```

---

# 📊 Models Evaluated

- Logistic Regression
- K-Nearest Neighbors
- Support Vector Machine (RBF)
- Random Forest
- XGBoost
- LightGBM
- CatBoost

After experimentation on the full dataset, the strongest ensemble models were selected for detailed analysis and optimization.

---

# 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Stratified K-Fold Cross Validation
- Confusion Matrix
- ROC Curve

---

# 📊 Explainable AI

To improve model interpretability, this project incorporates **Explainable AI (XAI)** techniques.

Implemented methods include:

- Mutual Information Analysis
- Model Feature Importance
- SHAP (SHapley Additive Explanations)

These analyses help explain **why** the model predicts a network flow as malicious rather than simply reporting a prediction.

---

# ⚙️ Technologies Used

### Programming

- Python

### Data Analysis

- NumPy
- Pandas

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn
- XGBoost
- LightGBM
- CatBoost
- imbalanced-learn

### Explainability

- SHAP

---

# 📁 Project Structure

```
📦 Intrusion-Detection-System
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── images/
├── model/
└── dataset/
```

---

# 🌟 Key Features

✅ Complete Research-Oriented Workflow

✅ Large Scale Dataset Handling (~701K Flows)

✅ Leak-Free Machine Learning Pipeline

✅ Cross Validation

✅ Hyperparameter Optimization

✅ Explainable AI

✅ Publication-Oriented Structure

✅ Easily Extendable to Full CIC-IDS2017 Dataset

---

# 🚀 Future Improvements

- Multi-Class Intrusion Detection
- Full CIC-IDS2017 (All 8 Traffic Files)
- CIC-IDS2018
- CIC-DDoS2019
- Deep Learning Models
- Autoencoder-based Anomaly Detection
- Real-Time Intrusion Detection
- REST API Deployment
- Docker Containerization
- Cloud Deployment

---

# 📚 Research Significance

This project establishes a scalable and reproducible machine learning framework for intelligent intrusion detection.

The workflow has been intentionally designed to support:

- Academic Research
- Machine Learning Experimentation
- Cybersecurity Analytics
- Explainable Artificial Intelligence
- Future Deployment as a Production IDS

---

# 🤝 Connect With Me

**Ali Kaisar Saiful**

Computer Science & Engineering

State University of Bangladesh

📧 Email: *amaksaiful007@gamil.com*

🌐 GitHub: https://github.com/Aksaiful007

💼 LinkedIn: *https://www.linkedin.com/in/ak-saiful-348152418/*

---

<div align="center">

## ⭐ If you found this project interesting, consider giving it a Star!

*"Machine Learning becomes truly valuable when its decisions are not only accurate, but also understandable and reproducible."*

</div>
