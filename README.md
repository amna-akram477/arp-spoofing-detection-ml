# Detection of MITM Attacks: A Machine Learning-Based Framework

## Overview

This project focuses on detecting ARP Spoofing-based Man-in-the-Middle (MitM) attacks using machine learning and deep learning techniques. It explores individual XGBoost and LSTM models alongside a hybrid approach to improve the detection of malicious network traffic.

The proposed approach analyzes network traffic patterns to distinguish between benign and attack traffic, with a focus on detection accuracy and reliable model evaluation.

## Research Highlights

- **Dataset:** Kitsune ARP MitM Dataset
- **Total Records:** 2,504,267
- **Features:** 115
- **Models:** XGBoost, LSTM, and Hybrid XGBoost-LSTM
- **Preprocessing:** StandardScaler
- **Validation:** Cross-validation to assess model generalization and overfitting.

## Model Performance

| Model | Accuracy |
|---|---:|
| XGBoost | 98% |
| LSTM | 97% |
| **Hybrid XGBoost-LSTM** | **99%** |

### Additional Evaluation Metrics

- **Matthews Correlation Coefficient (MCC):** 0.9683
- **False Positive Rate (FPR):** 0.0189

## Technologies & Tools

- Python
- Scikit-learn
- Pandas
- NumPy


## Repository Structure

```text
arp-spoofing-detection-ml/
│
├── README.md
├── paper/
│   └── Detection_of_MITM_Attacks__A_Machine_Learning_Based_Framework.pdf
├── notebooks/
├── src/
├── results/
├── requirements.txt
└── LICENSE
```

## Research Publication

**Detection of MITM Attacks: A Machine Learning-Based Framework**

The research paper is included in the `paper/` directory.

## Dataset

This project uses the Kitsune ARP MitM dataset for evaluating machine learning and deep learning approaches to ARP spoofing detection.

## Project Objective

To explore effective AI-driven approaches for identifying ARP spoofing attacks and improving the detection of Man-in-the-Middle threats in network environments.
