# Network Intrusion Detection System using Machine Learning

An end-to-end machine learning pipeline designed to detect cyber threats by classifying network traffic as normal or malicious. This project compares multiple supervised learning algorithms to identify the most effective model for intrusion detection.

---

## Project Overview

With the rapid growth of digital infrastructure, cyber attacks have become increasingly sophisticated. Intrusion Detection Systems (IDS) play a critical role in identifying malicious activities before they compromise network security.

This project applies machine learning and deep learning techniques to automatically analyze network traffic and detect potential threats with high accuracy.

### Workflow Includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding & scaling
- Model training
- Performance evaluation
- Comparative analysis

---

## Dataset

This project uses the **UNSW-NB15 dataset**, a widely recognized benchmark for network intrusion detection research.

**Download Dataset:**  
https://research.unsw.edu.au/projects/unsw-nb15-dataset

**Note:** The dataset is not included in this repository due to its size.

---

## Models Implemented

- Decision Tree
- Random Forest (Ensemble Learning)
- Support Vector Machine (SVM)
- Neural Network (TensorFlow / Keras)

Each model was evaluated using industry-standard classification metrics.

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|------------|-------------|----------|-------------|------------|
| Decision Tree | 89.54% | 98.11% | 86.30% | 91.83% | 0.914 |
| Random Forest | 90.08% | 98.78% | 86.49% | 92.23% | 0.985 |
| SVM | 79.46% | 92.39% | 76.09% | 83.45% | 0.926 |
| Neural Network | 89.40% | 97.19% | 86.93% | 91.78% | 0.977 |

---

## Best Performing Model

**Random Forest** delivered the strongest overall results with the highest Accuracy, F1 Score, and an exceptional ROC-AUC of **0.985**, demonstrating excellent capability in distinguishing between benign and malicious traffic.

The high ROC-AUC score highlights the model’s effectiveness in detecting cyber threats while minimizing misclassification.

---

## Key Insight

Ensemble methods like **Random Forest** outperformed individual models, emphasizing the importance of combining multiple decision trees for building robust intrusion detection systems.

---

## Tech Stack

### Languages & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

##  How to Run This Project

### Clone the Repository
```bash
git clone https://github.com/Ar9ab007cpu/intrusion-detection-system-ml.git
