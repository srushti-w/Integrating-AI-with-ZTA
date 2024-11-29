# AI-Based Threat Detection in Zero Trust Architecture

This repository contains the implementation of the project *AI-Based Threat Detection in Zero Trust Architecture (ZTA)*, developed as part of the **CS558 Advanced Computer Security** course. The project integrates Artificial Intelligence (AI) techniques into ZTA frameworks to enhance real-time threat detection and response in network traffic.

---

## Project Overview

### Objectives
1. Develop and train AI models for accurate threat detection in network traffic.
2. Integrate the AI module with core ZTA principles, emphasizing the "never trust, always verify" approach.
3. Implement real-time threat analysis capabilities for high accuracy and low latency.
4. Assess the scalability and adaptability of the solution.

### Key Features
- AI-based anomaly detection using machine learning algorithms like Random Forest and Neural Networks.
- Integration of AI models with ZTA principles, including continuous authentication and dynamic access control.
- Real-time threat detection pipeline for enhanced security monitoring.

---

## Dataset

The project uses network traffic datasets, including:
- Public cybersecurity datasets like UNSW-NB15 and CICIDS2017.
- Simulated network traffic data.

All datasets are preprocessed to handle missing values, normalize formats, and label normal/malicious traffic for supervised learning.

---

## Tools and Technologies

- **Programming Language**: Python
- **ML Libraries**: TensorFlow, Scikit-learn
- **Data Processing**: Pandas, NumPy
- **Testing and Monitoring**: Pytest, network traffic simulators
- **Version Control**: Git

---

## Implementation Details

### Data Preprocessing
1. Data cleaning and normalization.
2. Feature engineering to extract meaningful attributes.
3. Encoding of categorical labels (e.g., `Label` for normal/malicious traffic).

### AI Model Development
- **Random Forest**: Handles high-dimensional data for anomaly detection.
- **Neural Networks**: Captures complex patterns in network traffic.
- Hyperparameter tuning for optimized performance.

### Model Evaluation
- Metrics: Accuracy, Precision, Recall, F1-score, and AUC-ROC.
- Cross-validation to ensure robustness.
- Ensemble techniques for improved prediction accuracy.

### Real-Time Processing
- Integrated real-time threat detection pipelines.
- Adaptive security measures based on live network traffic analysis.

---

## Usage

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
