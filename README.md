# 🏢 HVAC Fault Detection using Machine Learning

> Machine Learning project developed as part of my MSc Data Analytics degree at London Metropolitan University.

This project analyses HVAC (Heating, Ventilation and Air Conditioning) operational data to detect equipment faults using Machine Learning techniques and interactive Power BI dashboards.


## 📌 Project Overview

Heating, Ventilation and Air Conditioning (HVAC) systems are responsible for a significant portion of a building's energy consumption. Faults in Fan Coil Units (FCUs) can lead to unnecessary energy waste, increased maintenance costs, and reduced system efficiency.

This project develops machine learning models to automatically detect HVAC faults using historical sensor data. Multiple classification algorithms were implemented and compared to identify the most effective approach for fault prediction.
The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Machine Learning Models
- Model Evaluation
- Power BI Dashboard
- Result Interpretation

---

## 🎯 Project Objectives

- Detect faults in HVAC Fan Coil Units (FCUs)
- Perform Exploratory Data Analysis (EDA)
- Compare multiple Machine Learning algorithms
- Evaluate model performance using standard classification metrics
- Improve predictive accuracy for early fault detection

---

## 📊 Dataset

The dataset consists of HVAC sensor readings collected from a commercial building.

### Dataset Information

- Building HVAC operational data
- 731 Fan Coil Units (FCUs)
- 628 preprocessed fault-related files
- Over **1 million sensor records**
- Multiple temperature and operational attributes
- Binary classification:
  - **0 → Normal Operation**
  - **1 → Fault Detected**

### Main Features

- Derived
- Attr_Name
- ID
- DateTime
- Value

---

# 🛠 Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn, Power BI |
| Machine Learning | Scikit-learn, TensorFlow/Keras |
| Development | Jupyter Notebook |

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed before model training:

- Histogram
- Count Plot
- Heatmap
- Correlation Analysis
- Feature Distribution
- Power BI Dashboard

The EDA helped understand the data distribution, identify class imbalance, detect outliers, and explore relationships between HVAC sensor variables.

---

# 🤖 Machine Learning Models

The following models were implemented and compared:

- ✅ Support Vector Machine (SVM)
- ✅ K-Nearest Neighbours (KNN)
- ✅ Multilayer Perceptron (MLP)
- ✅ Deep Multilayer Perceptron (Deep MLP)

---

# 📏 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Different train-test splits were evaluated:

- 70% Training / 30% Testing
- 80% Training / 20% Testing

Label Noise was also introduced to reduce overfitting and evaluate model robustness.

---

# 📊 Results Summary

| Model | Accuracy |
|--------|----------|
| KNN | 99% |
| SVM | 99% |
| MLP | 99% |
| Deep MLP | High Accuracy (varied by configuration) |

The MLP model demonstrated the most consistent performance across different train-test splits while maintaining high precision and recall.

---

# 📷 Project Visualizations

The project includes:

- Histogram
- Box Plot
- Count Plot
- Heatmap
- Confusion Matrices
- Power BI Dashboard

These visualizations are available in the **images/** folder.

---

# 📂 Repository Structure

```
hvac-fault-detection-ml/

├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt
│
├── data/
│     hvac_sample_data.xlsx
│
├── images/
│     histogram.png
│     heatmap.png
│     count_plot.png
│     boxplot.png
│     powerbi_dashboard.png
│     knn_confusion_matrix.png
│     svm_confusion_matrix.png
│
├── notebooks/
│     HVAC_Fault_Detection.ipynb
│
└── reports/
      HVAC_Fault_Detection_Project_Report.pdf
```

---

# 🚀 How to Run

1. Clone this repository

```
git clone https://github.com/your-username/hvac-fault-detection-ml.git
```

2. Install required libraries

```
pip install -r requirements.txt
```

3. Open the notebook

```
jupyter notebook
```

4. Run all notebook cells.

---

# 📌 Future Improvements

- Real-time HVAC fault monitoring
- Streamlit Web Application
- Hyperparameter Optimization
- Explainable AI (SHAP/LIME)
- Cloud Deployment
- IoT Sensor Integration

---

# 👩‍💻 Author

**Padmaja Rohan Deshpande**

🎓 MSc Data Analytics Graduate

**Skills**

- Python
- SQL
- Machine Learning
- Power BI
- Data Visualization
- Data Analysis

---

# 📄 License

This project was developed as part of my MSc Data Analytics dissertation and is shared for educational and portfolio purposes.
