# GNNAnomalyDetection
##Problem Statement 
A manufacturing process follows a strict sequence of tasks (Task 1 → Task 2 → Task 3) requiring specific machines (M1 → M2 → M3). Deviations from this workflow, such as unexpected machine activation or worker allocation errors, can disrupt production. This system uses  Graph Neural Networks (GNNs)  to detect anomalies while accommodating adaptive behaviors (e.g., temporary use of M3 during Task 1 for high-density materials).  

##1. Setup Guide
###1.1 Prerequisites
•	Python: 3.8+
•	Libraries:
pip install torch torch-geometric pandas numpy matplotlib seaborn scikit-learn
•	Dataset: Save as manufacturing_test_data.csv in the working directory.
###1.2 File Structure
project/  
├── manufacturing_test_data.csv  
├── anomaly_detection.py  
└── requirements.txt  
###1.3 Execution
python anomaly_detection.py
