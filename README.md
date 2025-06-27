# 🌊 The Ocean CleanUp - Machine Learning Project

This project is part of a supervised machine learning lab focused on predicting whether a river is a **high or low contributor of plastic waste** to the ocean based on various features.

---

## 📌 Project Objective

The goal is to:
- Analyze river plastic pollution data collected by [The Ocean Cleanup](https://theoceancleanup.com/)
- Build a supervised classification model that predicts plastic contribution class: **High (0)** or **Low (1)**
- Evaluate the model with proper performance metrics

---

## 🧪 Dataset Description

- **Source**: [The Ocean Cleanup Research Paper](https://www.science.org/doi/10.1126/sciadv.aaz5803)
- **Columns** include:
  - Country, river name, rainfall, population, distance to ocean, etc.
  - `'M[E] (metric tons year -1)'` (used to derive target)
- **Target column**:
  - `plastic_contribution` (created from `'M[E] (metric tons year -1)'`)
    - `0` = High contributor (plastic > 6008)
    - `1` = Low contributor (plastic ≤ 6008)

---

## 🧰 Tech Stack

- **Language**: Python 🐍
- **Libraries**:
  - `pandas`, `numpy`, `scikit-learn`
  - `matplotlib`, `seaborn` (for visualization)
- **Environment**: Jupyter Notebook / Google Colab

---

## 📁 Project Structure
The_Ocean_CleanUp/
│
├── data/ # Raw and cleaned datasets (ignored in Git)
├── notebooks/ # Jupyter Notebooks
│ └── lab_task_1.ipynb # Supervised learning task
├── scripts/ # Python scripts (e.g., data cleaning, model training)
├── models/ # Saved models (.pkl or .joblib, ignored)
├── requirements.txt # Project dependencies
├── .gitignore # Files and folders ignored by Git
└── README.md # Project documentation


---

## 🚀 Instructions to Run

1. **Clone the repo**:
   ```bash
   git clone https:/github.com/aprilyab/The_-Ocean_CleanUp.git
   cd The_-Ocean_CleanUp

Model Overview
Algorithm used: Logistic Regression

    Evaluation metrics:

    Accuracy

    Precision

    Recall

    Confusion matrix

    ROC-AUC

Contact
Project by: Your Name
📧 Email: henokapril@gmail.com
💼 GitHub: https://github.com/aprilyab/The_-Ocean_CleanUp  



