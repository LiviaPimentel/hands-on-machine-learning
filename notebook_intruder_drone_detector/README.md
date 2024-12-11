# Drone Detection Using Encrypted Wi-Fi Traffic Data

## Overview

This project explores the **application of Machine Learning techniques** to detect invading drones based on encrypted Wi-Fi traffic data. By analyzing patterns in wireless signals, the goal is to classify whether a detected Wi-Fi signal originates from a drone or another source, enabling effective drone monitoring and mitigation strategies.

This work was presented at SIGE conference: (Paper)[https://www.researchgate.net/publication/362243302_Deteccao_de_Drones_Intrusos]

---

## Methodology

The detection pipeline involves the following steps:

1. **Exploratory Data Analysis (EDA)**:
   - Analyzed the encrypted Wi-Fi traffic data to identify trends, anomalies, and relevant features for drone detection.
   
2. **Data Pre-Processing**:
   - Applied data cleaning techniques to handle missing or noisy data.
   - Standardized and normalized features for improved model performance.
   
3. **Model Development and Validation**:
   - Trained various **Machine Learning models** to classify Wi-Fi signals.
   - Performed hyperparameter tuning and cross-validation to ensure robust performance.
   - Evaluated models using metrics such as accuracy, precision, recall, and F1-score.

---

## Dataset

The dataset used in this project was sourced from the following link:
[Encrypted Wi-Fi Traffic Data for UAV Detection](http://mason.gmu.edu/~lzhao9/materials/data/UAV/)

### Dataset Highlights:
- Contains encrypted Wi-Fi traffic data captured from various sources, including drones.
- Features signal characteristics useful for identifying patterns specific to UAVs.
- Enables development of robust Machine Learning models for drone detection.

---

## Applications and Impact

The ability to detect drones using encrypted Wi-Fi traffic has significant implications across industries:

- **Security and Surveillance**:
  - Monitor restricted areas such as airports, military zones, or sensitive facilities.
  - Prevent unauthorized drone activity in high-security environments.

- **Airspace Management**:
  - Enhance drone traffic monitoring systems for urban and commercial airspace.
  - Ensure compliance with regulatory frameworks for UAV operations.

- **Public Safety**:
  - Detect and mitigate potential drone-based threats during events or in crowded areas.

