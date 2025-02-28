# GNNAnomalyDetection

## Overview
This project uses **Graph Neural Networks (GNNs)** to detect anomalies in a manufacturing process. The workflow follows a strict sequence of tasks (**Task 1 → Task 2 → Task 3**) requiring specific machines (**M1 → M2 → M3**). The system identifies deviations such as unexpected machine activation or worker allocation errors while allowing for adaptive behaviors (e.g., temporary use of M3 during Task 1 for high-density materials).

## 1. Setup Guide

### 1.1 Prerequisites
Ensure you have the following dependencies installed:

- **Python**: 3.8+
- **Required Libraries**: Install via pip:
  ```bash
  pip install torch torch-geometric pandas numpy matplotlib seaborn scikit-learn
  ```
- **Dataset**: Save the dataset as `manufacturing_test_data.csv` in the working directory.

### 1.2 File Structure
Your project directory should be structured as follows:
```
project/
├── manufacturing_test_data.csv
├── anomaly_detection.py
└── requirements.txt
```

### 1.3 Execution
To run the anomaly detection script, execute:
```bash
python anomaly_detection.py
```

