
# Malware Detection - MLP Project T12025

This is a Machine Learning project submitted for the **IITM BS Degree Program (T12025)**. The task is to predict whether a system is infected by malware based on telemetry data from antivirus reports.

## 📁 Project Structure

- `21f1001234-notebook-t12025.ipynb` - Final notebook used in the competition
- `submission.csv` - Final predictions in the required format
- `train.csv`, `test.csv`, `sample_submission.csv` - Provided datasets
- Note:- Due to large size of train dataset it can't be uploaded here so you can download it from kaggle page of this competetion.

## 🧠 Problem Statement

Predict a system’s probability of getting infected by various families of malware, based on machine-specific features and telemetry data. The dataset contains ~150 system attributes like:

- Product and OS version info
- Device hardware features (RAM, processor, display)
- Security configuration (Firewall, Secure Boot, TPM, etc.)

## 📊 Dataset

Files:
- `train.csv` – With target labels (0/1)
- `test.csv` – Without target, for submission
- `sample_submission.csv` – Sample output format

Target column:
- `target` (0 = No Malware, 1 = Malware Detected)

Each row represents a unique machine identified by `MachineID`.

## 🛠️ Libraries Used (There was a strict boundation , that only these libraries can be  used .)

- `NumPy`
- `Pandas`
- `Matplotlib`
- `Seaborn`
- `scikit-learn`
- `XGBoost`
- `LightGBM`
- `Imblearn` (for handling class imbalance)

## ⚙️ ML Pipeline

1. **Data Cleaning** – Removed/Imputed nulls, encoded categorical features.
2. **EDA** – Explored class distribution, correlations.
3. **Feature Engineering** – Label encoding, scaling, etc.
4. **Modeling** – Tried XGBoost, LightGBM, RandomForest.
5. **Evaluation** – Used `accuracy_score` as required.
6. **Submission** – Saved predictions in the required `id` and `target` format.

## ✅ Results

Achieved an accuracy of **0.63670
** on test set .

## 🗂️ Competition Details

- Hosted on: Kaggle (Private IITM Competition)
- Duration: Dec 26, 2024 – Mar 19, 2025
- Evaluation Metric: `accuracy_score`



---

## 🔗 Links

- [Kaggle ](#)https://www.kaggle.com/competitions/System-Threat-Forecaster/overview
- [train.csv link] /https://www.kaggle.com/competitions/System-Threat-Forecaster/data?select=train.csv

---

## 👨‍💻 Author

- **Name**: Harsh Kumar   
- [GitHub](https://github.com/22f3001316)  
- [LinkedIn](https://www.linkedin.com/in/harsh-kumar-b20633233)

---


