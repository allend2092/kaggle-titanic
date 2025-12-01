# Kaggle Titanic — Data Science & ML Practice (Local + WSL)

This repository contains my local end-to-end workflow for the **Kaggle Titanic competition**, built in **WSL (Ubuntu) with a Python virtual environment**.
  
  
Visit my Kaggle page: https://www.kaggle.com/daryla/competitions  
  
## Project Structure
Machine_Learning_Education/Projects/kaggle_titanic/  
├── data/  
│ └── raw/ # Original Kaggle datasets (not committed to git)  
├── notebooks/  
│ └── daryls_kaggle_titanic.ipynb # EDA + XGBoost training pipeline  
├── src/ # Future Python modules & ML pipelines  
├── reports/ # Future analysis outputs / model evaluations  
└── README.md #  

## Completed Work
- Downloaded data using the **Kaggle CLI**
- Performed **Exploratory Data Analysis (EDA)**
- Filled missing values **per passenger class**
- Built initial ML pipeline using **XGBoost**
- Executed workflow locally in **JupyterLab within WSL**
- Created and verified my **Kaggle submission file**

## Next Steps Planned
I will continue iterating on:
- Feature engineering (Cabin, Family size, Ticket)
- Cross-validation
- Hyperparameter tuning
- Model experimentation (XGBoost, Random Forest, etc.)
- Optional CI/CD workflows via GitHub Actions (not yet added)

## Environment
| Component | Spec |
|---|---|
| OS | Windows 11 → WSL2 (Ubuntu) |
| Python | 3.12 in Virtual Environment |
| GPU | Nvidia RTX 3060 (12GB) + RTX 3090 (24GB) |
| ML Libraries | pandas, numpy, xgboost, scikit-learn, matplotlib |


## Purpose
This is a personal learning project to practice:
- Data Science fundamentals
- Machine Learning models
- Reproducible project layouts
- GitHub-managed development from WSL

---

_“The goal is not perfection, the goal is progress.”_

Feel free to explore and leave feedback!
