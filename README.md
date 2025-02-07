# Network Intrusion and Ransomware Detection for SecureTech Solutions Inc.

This repository presents an advanced approach to network intrusion and ransomware detection, tailored to address the growing sophistication of cyberattacks targeting SecureTech Solutions Inc.'s clients. Leveraging machine learning techniques and exploratory data analysis, this project delivers actionable insights to enhance cybersecurity defenses, reduce false alarms, and provide explainable predictions to cybersecurity analysts.

![image](https://github.com/user-attachments/assets/eaeff26e-860a-4f3f-82b7-c8bd35179fb6)

---

## Table of Contents
1. [Overview](#overview)
2. [Rationale for the Project](#rationale-for-the-project)
3. [Objectives](#objectives)
4. [Data Description](#data-description)
5. [Tech Stack](#tech-stack)
6. [Project Scope](#project-scope)
7. [Methodology](#methodology)
8. [Results](#results)
9. [Recommendations](#recommendations)
10. [Future Work](#future-work)
11. [Conclusion](#conclusion)

---

## 1. Overview
In recent times, SecureTech Solutions Inc. has experienced a significant surge in ransomware attacks targeting its clients. These attacks exhibit high levels of sophistication, frequently bypassing conventional security measures. Beyond their financial implications, these incidents threaten SecureTech's reputation, posing a serious challenge to the trust they have cultivated over the years.

This project focuses on the development of an effective **Network Intrusion Detection System (NIDS)** to combat these threats. By applying machine learning models, this project aims to identify and mitigate ransomware and network intrusions in real-time, safeguarding critical assets and preserving client trust.

---

## 2. Rationale for the Project
Ransomware attacks are increasingly preceded by network intrusions, highlighting the critical need for robust detection mechanisms. Key reasons for developing this system include:

- **Preventing Financial Losses**: Avoiding costs associated with ransom payments, downtime, and recovery efforts.
- **Safeguarding Sensitive Data**: Protecting confidential information from exposure or theft.
- **Preserving Business Continuity**: Minimising disruptions caused by attacks.
- **Maintaining Customer Trust**: Ensuring clients’ confidence in SecureTech’s ability to protect their data.
- **Regulatory Compliance**: Meeting legal obligations for data protection.
- **Adapting to Evolving Threats**: Addressing sophisticated intrusion tactics with state-of-the-art detection systems.

---

## 3. Objectives
- **Develop an Effective Network Intrusion Detection System (NIDS)**: Accurately detect ransomware attacks in real-time.
- **Minimise False Positives and False Negatives**: Reduce false alarms and enhance detection accuracy.
- **Ensure Explainable Predictions**: Provide insights to cyber analysts regarding the factors driving malware attacks.

---

## 4. Data Description
The dataset contains features critical for network traffic analysis, such as:
- **Connection Metrics**: Ports, protocols, and flow duration.
- **Packet Details**: Total packets transmitted forward and backward, sizes, and speeds.
- **Statistical Metrics**: Mean, maximum, and standard deviation of packet sizes and interarrival times.
- **Flags and Ratios**: FIN, SYN, and ACK flag counts, download/upload ratios, and segment sizes.

For a complete list of features, see the full dataset description in the repository.

---

## 5. Tech Stack
The project is implemented using the following technologies and libraries:
- **Programming Language**: Python
- **Libraries**:
  - **NumPy**: Numerical computations
  - **Pandas**: Data manipulation
  - **Matplotlib & Seaborn**: Data visualisation
  - **PySpark**: Distributed data processing and machine learning

---

## 6. Project Scope
The scope of this project includes:
1. **Exploratory Data Analysis (EDA)**: Statistical analysis and visualisation to understand patterns, correlations, and anomalies in the data.
2. **Feature Selection**: Identifying the most relevant features for accurate predictions.
3. **Model Development**: Applying machine learning techniques to build predictive models.
4. **Model Evaluation and Selection**: Assessing models using performance metrics and selecting the best-performing one for deployment.

---

## 7. Methodology
The project follows these steps:
1. **Data Preprocessing**:
   - Cleaning and normalising data.
   - Encoding categorical features.
2. **Exploratory Data Analysis (EDA)**:
   - Visualising feature distributions and correlations.
   - Identifying patterns and anomalies.
3. **Feature Engineering**:
   - Selecting top features based on statistical relevance.
4. **Model Development**:
   - Training machine learning models, including logistic regression, random forests, and gradient boosting.
   - Fine-tuning hyperparameters for optimal performance.
5. **Evaluation**:
   - Using metrics like accuracy, precision, recall, and F1-score to assess model performance.
   - Minimising false positives and negatives to enhance reliability.

---
## Project Visualizations

### Attack Distribution Analysis
![Attack Types Distribution](./1.png)
*Distribution of different attack types in the dataset showing DDoS, Normal traffic, Probe attacks, DoS, BFA and U2R*

### Feature Correlation Matrix
![Feature Correlation Heatmap](./2.png)
*Correlation matrix showing relationships between key network traffic features*

### Model Performance Metrics
![Model Performance Comparison](./3.png)
*Comparison of accuracy, precision, recall and F1 scores across different models*

### Feature Importance Analysis
![Feature Importance](./4.png)
*Top features contributing to normal traffic classification*

---
## 8. Results
Key findings include:
- **High Precision**: The model effectively identifies malicious activities with minimal false alarms.
- **Feature Importance**: Key indicators of intrusion include packet size variations, flow durations, and specific protocol flags.
- **Scalability**: The use of PySpark ensures the system can handle large-scale network data efficiently.

---

## 9. Recommendations
To strengthen cybersecurity defenses, it is recommended to:
1. **Implement Real-Time Monitoring**: Deploy the NIDS for continuous analysis of network traffic.
2. **Enhance Training**: Regularly update models with new intrusion patterns to maintain effectiveness.
3. **Integrate Threat Intelligence**: Incorporate external threat intelligence to improve detection capabilities.

---

## 10. Future Work
Potential areas for future development include:
- Incorporating deep learning techniques for improved accuracy.
- Expanding the system to detect additional types of cyberattacks.
- Developing a dynamic visualisation dashboard for real-time monitoring and reporting.

---

## 11. Conclusion
This project provides a robust solution for detecting and mitigating ransomware and network intrusions. By leveraging machine learning techniques, the system enhances SecureTech's ability to protect critical assets, maintain business continuity, and uphold client trust in an evolving cybersecurity landscape.

---
