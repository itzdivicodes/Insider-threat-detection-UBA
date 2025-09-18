Insider Threat Detection

Team Name: Quatrix
Team Member: Divya Pugalendiran, Hemila Saravanan, Bodhana A, and Lokireddy Madhavi

📌 Overview

This project detects insider threats by analyzing three core activity logs. Machine-learning models flag suspicious patterns such as unusual logins, unexpected file access, and abnormal application usage to help prevent internal security breaches.

🚀 Features

Three-Source Data Integration: Merges

login.csv – user login/logout events

file_access.csv – file access records

application_usage.csv – application start/end logs

GRU Autoencoder: Unsupervised anomaly detection.

Federated Learning (FedAvg): Simulated privacy-preserving training across nodes.

Random Forest Detector: Final supervised classification and validation.

🏗️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, TensorFlow/PyTorch, Matplotlib

Environment: Google Colab (all notebooks and scripts can be run end-to-end in Colab—no local setup required)

⚙️ Methodology

Preprocessing – Cleaned, normalized, and engineered features from the three datasets.

Modeling –

GRU Autoencoder for anomaly detection

Federated Learning (FedAvg) for distributed privacy

Random Forest for supervised threat detection

Evaluation – Accuracy, confusion matrix, and classification metrics.

📊 Results

High detection accuracy with minimal false positives.

Federated learning performed on par with centralized training while preserving privacy.
