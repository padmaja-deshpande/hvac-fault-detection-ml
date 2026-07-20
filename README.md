# HVAC Fault Detection and Predictive Maintenance using Machine Learning
![Python](https://img.shields.io/badge/Python-3.10-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-MachineLearning-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)
![License](https://img.shields.io/badge/License-MIT-green)
Machine Learning project developed as part of my **MSc Data Analytics** degree at **London Metropolitan University**.

This project analyses HVAC (Heating, Ventilation and Air Conditioning) operational data to detect equipment faults using Machine Learning techniques and interactive Power BI dashboards.
---

# Table of Contents

- Project Overview
- Project Objectives
- Business Problem
- Dataset
- Technologies Used
- Exploratory Data Analysis
- Machine Learning Models
- Results Summary
- Power BI Dashboard
- Repository Structure
- How to Run
- Future Improvements
- Author

- ---

# Project Overview

Heating, Ventilation and Air Conditioning (HVAC) systems are responsible for a significant portion of a building's energy consumption.

Faults in Fan Coil Units (FCUs) can lead to unnecessary energy waste, increased maintenance costs, and reduced system efficiency.

This project develops Machine Learning models to automatically detect HVAC faults using historical sensor data.

The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Machine Learning
- Model Evaluation
- Power BI Dashboard
- Result Interpretation
- ---

# Project Objectives

- Detect faults in HVAC Fan Coil Units (FCUs)
- Perform Exploratory Data Analysis (EDA)
- Compare Machine Learning algorithms
- Evaluate model performance
- Improve predictive maintenance
- ---

# Business Problem

HVAC systems consume significant amounts of energy in commercial buildings.

Unexpected equipment failures increase maintenance costs, energy consumption and operational downtime.

Early fault detection enables maintenance teams to identify problems before system failure occurs, improving efficiency and reducing costs.
---

# Dataset

The dataset contains HVAC operational sensor data collected from commercial buildings.

## Dataset Information

- HVAC operational sensor data
- 731 Fan Coil Units (FCUs)
- 628 fault-related datasets
- Over one million sensor records
- Binary Classification
  - 0 = Normal Operation
  - 1 = Fault Detected
  - ---

# Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Power BI |
| Machine Learning | Scikit-learn, TensorFlow/Keras |
| Development | Jupyter Notebook |
---

# 📊 Power BI Dashboard

The interactive Power BI dashboard provides insights into HVAC system performance, fault distribution, and model outputs.

![Power BI Dashboard](images/powerbi_dashboard.png)
---

# 📈 Exploratory Data Analysis (EDA)

Before building machine learning models, exploratory data analysis was performed to understand the dataset, identify outliers, detect class imbalance, and explore relationships between variables.

## Histogram

![Histogram](images/histogram.png)

---

## Heatmap

![Heatmap](images/heatmap.png)

---

## Count Plot

![Count Plot](images/count_plot.png)

---

## Box Plot

![Box Plot](images/boxplot.png)
---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)
- Multilayer Perceptron (MLP)
- Deep Multilayer Perceptron (Deep MLP)
- ---

# 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## KNN Confusion Matrix

![KNN Confusion Matrix](images/knn_confusion_matrix.png)

---

## SVM Confusion Matrix

![SVM Confusion Matrix](images/svm_confusion_matrix.png)
---

# 📋 Results Summary

| Model | Accuracy |
|--------|---------:|
| K-Nearest Neighbours (KNN) | 99% |
| Support Vector Machine (SVM) | 99% |
| Multilayer Perceptron (MLP) | 99% |
| Deep Multilayer Perceptron | High Accuracy |

### Key Findings

- Successfully detected HVAC faults using machine learning.
- Achieved high classification accuracy across multiple algorithms.
- Built an interactive Power BI dashboard for data visualization.
- Demonstrated predictive maintenance techniques for HVAC systems.
- ---

# 📂 Repository Structure

```text
hvac-fault-detection-ml/

├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
├── data/
├── images/
├── notebooks/
└── reports/
```
---

# 🚀 How to Run

## 1. Clone the repository

```bash
git clone https://github.com/padmaja-deshpande/hvac-fault-detection-ml.git
```

## 2. Install the required packages

```bash
pip install -r requirements.txt
```

## 3. Open the notebook

```bash
jupyter notebook
```

## 4. Run all notebook cells.
---

# 🚀 Future Improvements

- Real-time HVAC fault monitoring
- Streamlit dashboard deployment
- Hyperparameter optimization
- Explainable AI (SHAP/LIME)
- Cloud deployment (AWS/Azure)
- IoT sensor integration
- ---

# 👩‍💻 Author

**Padmaja Rohan Deshpande**

🎓 MSc Data Analytics Graduate

### Skills

- Python
- SQL
- Machine Learning
- Power BI
- Data Visualization
- Data Analysis

### Connect with Me

- GitHub: https://github.com/padmaja-deshpande
- LinkedIn: https://www.linkedin.com/in/padmaja-deshpande-2267b3165/
