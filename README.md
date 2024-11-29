# AI-Based Threat Detection in Zero Trust Architecture

This repository hosts the implementation of the project *AI-Based Threat Detection in Zero Trust Architecture (ZTA)*, developed as part of the **CS558 Advanced Computer Security** course. The project leverages Artificial Intelligence (AI) to enhance real-time threat detection and response in network traffic, integrating these capabilities into ZTA principles to bolster cybersecurity.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Key Features](#key-features)
4. [Dataset](#dataset)
5. [Tools and Technologies](#tools-and-technologies)
6. [Implementation Details](#implementation-details)
7. [Usage](#usage)
8. [Results](#results)
9. [Future Work](#future-work)
10. [License](#license)
11. [Contact](#contact)

---

## Project Overview

Traditional perimeter-based security models are increasingly ineffective in countering sophisticated cyber threats. Zero Trust Architecture (ZTA) operates under the principle of "never trust, always verify," offering a robust alternative. This project focuses on integrating AI into ZTA frameworks to address modern cybersecurity challenges such as anomaly detection, real-time threat analysis, and automated responses.

---

## Objectives

1. Develop AI models for accurate threat detection in network traffic.
2. Integrate AI with ZTA principles, emphasizing continuous authentication and dynamic access control.
3. Enable real-time threat analysis with minimal latency.
4. Optimize the system for scalability and adaptability to diverse network environments.

---

## Key Features

- **Anomaly Detection**: Machine learning-based detection of suspicious activities in network traffic.
- **Real-Time Analysis**: Streamlined pipelines for live data processing.
- **Dynamic Access Control**: Adaptive security policies driven by AI models.
- **Integration with ZTA Principles**: Application of continuous monitoring and least privilege access.

---

## Dataset

The project utilizes network traffic datasets for training and evaluation, including:
- **Public Datasets**: UNSW-NB15, CICIDS2017, and others.
- **Simulated Data**: Synthetic network traffic for controlled experimentation.

Preprocessing includes:
1. Cleaning and normalization.
2. Feature engineering for attributes like packet size and inter-arrival times.
3. Labeling of traffic as normal or malicious for supervised learning.

---

## Tools and Technologies

- **Programming Language**: Python
- **Machine Learning Libraries**: TensorFlow, Scikit-learn
- **Data Processing**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Testing**: Pytest, network traffic simulators
- **Version Control**: Git

---

## Implementation Details

### Data Preprocessing
1. Handle missing values and normalize data.
2. Encode categorical labels for classification tasks.
3. Extract features from raw network data.

### AI Model Development
- **Random Forest**: Handles high-dimensional data efficiently.
- **Neural Networks**: Captures complex patterns for anomaly detection.
- Hyperparameter tuning for model optimization.

### Model Evaluation
- Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC.
- Cross-validation ensures robustness.
- Ensemble techniques enhance prediction accuracy.

### Real-Time Processing
- Integration with ZTA for live threat detection.
- Adaptive security policies based on risk assessment.

---

## Usage

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Code
1. **Prepare the Dataset**:
   - Place the dataset (`combined_data.csv`) in the project directory.
   - Update the dataset path in the scripts.

2. **Train Models**:
   ```bash
   python train_models.py
   ```

3. **Real-Time Threat Detection**:
   ```bash
   python real_time_detection.py
   ```

4. **Evaluate Models**:
   ```bash
   python evaluate_models.py
   ```

---

## Results

### Model Performance
- **Random Forest Classifier**:
  - Accuracy: 98.57%
  - Precision: 94%
  - Recall: 94%
  - F1-Score: 94%
  
- **Neural Network**:
  - Accuracy: 97.14%
  - Precision: 93.18%
  - Recall: 82%
  - F1-Score: 87.23%

These results demonstrate the effectiveness of the AI-based threat detection module.

---

## Future Work

1. **Expanded ZTA Components**:
   - Network access control systems.
   - Real-time monitoring dashboards.

2. **Autonomous Security Systems**:
   - Fully automated threat detection and response mechanisms.

3. **Integration with Emerging Technologies**:
   - Blockchain for secure authentication.
   - Quantum computing for advanced encryption.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Contact

**Author**: Srushti Waichal  
**Email**: srushtiwaichal@gmail.com

For any queries, feel free to reach out!

---

## References

1. Cisco. "Annual Internet Report (2018–2023)."  
2. Rose, S., et al. "Zero Trust Architecture." NIST SP 800-207.  
3. Buczak, A. L., & Guven, E. "A Survey of Data Mining and Machine Learning Methods for Cybersecurity Intrusion Detection."  
4. Ying, W., et al. "Artificial Intelligence in the Cybersecurity Domain: Current Applications and Future Directions."  

Additional references can be found in the project documentation
