# Marine Engine Anomaly Detection using Machine Learning

## Overview

This project applies statistical and unsupervised machine learning techniques to detect anomalous operating conditions in a marine diesel engine dataset.

The objective is to identify abnormal sensor patterns that may support predictive maintenance, reduce downtime and improve operational reliability.

The project combines data-driven anomaly detection with engineering interpretation of marine engine subsystems.

## Dataset

The dataset contains 19,535 observations from six numerical ship engine sensors:

- Engine RPM
- Lubrication oil pressure
- Fuel pressure
- Coolant pressure
- Lubrication oil temperature
- Coolant temperature

Each observation represents the operating state of the engine at a given moment.

## Methods

The following methods were used:

- Exploratory Data Analysis
- Interquartile Range method
- One-Class Support Vector Machine
- Isolation Forest
- Principal Component Analysis
- Engineering interpretation of detected anomaly patterns

## Workflow

```text
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
IQR Outlier Detection
     ↓
One-Class SVM
     ↓
Isolation Forest
     ↓
PCA Visualisation
     ↓
Engineering Interpretation
     ↓
Predictive Maintenance Recommendations

```

## Project Resources

- 📑 **Final Report:** [Marine Engine Anomaly Detection Report](report/Marine_Engine_Anomaly_Detection_Report.pdf)

- 📓 **Jupyter Notebook:** [Anomaly Detection Notebook](notebook/marine_engine_anomaly_detection.ipynb)

---
