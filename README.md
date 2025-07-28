#  Heart Disease Prediction-Machine Learning

This project, developed by **Evan Lemuel**, demonstrates how to use machine learning to predict the presence of heart disease in patients based on clinical features. The notebook walks through the complete ML workflow using Python libraries like **Scikit-learn**, **Pandas**, and **NumPy**.

---

## Table of Contents

- [Problem Statement](#-problem-statement)
- [ Dataset](#-dataset)
- [ Tools & Libraries Used](#-tools--libraries-used)
- [ Project Structure](#-project-structure)
- [ How to Run](#️-how-to-run)
- [ Model Performance](#-model-performance)
- [ Future Enhancements](#-future-enhancements)
- [ License](#-license)

---

## Problem Statement

> **"Given clinical parameters about a patient, can we predict whether or not they have heart disease?"**

This is a classic binary classification problem. The output is:
- **1** → Presence of heart disease
- **0** → No heart disease

---

##  Dataset

- **Source**: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Attributes**: Age, Sex, Chest Pain Type, Cholesterol, Max Heart Rate, ST Depression, etc.
- **Format**: CSV
- **Shape**: 303 rows × 14 columns

---

## Tools & Libraries Used

- **Python 3.**  
- [Scikit-learn](https://scikit-learn.org/) – ML algorithms and metrics  
- [Pandas](https://pandas.pydata.org/) – Data handling  
- [NumPy](https://numpy.org/) – Numerical operations  
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) – Visualization

---

##  Project Structure

```bash
heart-disease-classification/
├── heart_disease_prediction.ipynb   # Main notebook
├── data/
│   └── heart.csv                    # Dataset
├── models/                          # (Optional) saved models
├── README.md                        # Project documentation
├── requirements.txt                 # Python packages
└── LICENSE                          # License file
