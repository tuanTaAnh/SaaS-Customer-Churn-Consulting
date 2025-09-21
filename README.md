# SaaS Customer Churn Consulting  

## Project Overview  
This project analyzes customer churn data for a B2B SaaS company. The goal is to identify key churn drivers, segment customers, and recommend data-driven retention strategies.  

The analysis was completed in Python using **Jupyter Notebook** and includes:  
- Data quality checks and preprocessing.  
- Exploratory Data Analysis (EDA) with visualizations.  
- Statistical insights into churn behavior.  
- Predictive modeling with **RandomForest + SHAP** for interpretability.  
- Customer segmentation using **KMeans clustering + PCA**.  

---

## Repository Structure  
```
├── Dataset/ # Input dataset (CSV) 
├── [Application] Final Project.ipynb # Main analysis notebook
├── requirements.txt # Python dependencies
└── README.md # Project documentation
```

---

## Installation  

Clone the repository:  
```bash
git clone https://github.com/tuanTaAnh/SaaS-Customer-Churn-Consulting.git
cd SaaS-Customer-Churn-Consulting
```

## Create a virtual environment and install dependencies:
```bash
conda create -n churn python=3.12
conda activate churn
pip install -r requirements.txt
```

## Open the Jupyter Notebook:
```bash
jupyter notebook "[Application] Final Project.ipynb"
```

## Tech Stack
1. Python, Jupyter Notebook
2. pandas, numpy, seaborn, matplotlib
3. scikit-learn, shap
4. KMeans clustering, PCA

## Deliverables

- Cleaned and processed dataset.
- EDA with visual and statistical insights.
- Churn prediction with feature importance.
- Segmentation of customers into actionable clusters.
- Final business recommendations.

