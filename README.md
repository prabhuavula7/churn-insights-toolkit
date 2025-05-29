# Customer Churn Prediction & Strategy Simulation

This project focuses on predicting customer churn using machine learning techniques. It covers the complete ML pipeline — from data cleaning and EDA to modeling, A/B testing, and explainability.

## Project Scope

- Data preprocessing & cleaning
- Exploratory Data Analysis (EDA)
- Feature engineering & encoding
- ML model training & evaluation (Logistic Regression, XGBoost)
- Threshold tuning & confusion matrix analysis
- Profit curve and ROI simulation
- SHAP analysis for interpretability
- Simulated A/B test to measure impact of Tech Support
- ROI estimation on simulated intervention

## Files

- `data` folder with the raw dataset I used
- `eda.ipynb` – Complete notebook including EDA, modeling, SHAP, and A/B testing
- `requirements.txt` – Project dependencies
- `.gitignore` – Excludes virtual environment and temp files

## Model Insights

- Optimized threshold: 0.45
- Precision: 0.54 | Recall: 0.53 | F1: 0.54 for churn class
- Key drivers of churn: MonthlyCharges, tenure, Contract type, TechSupport

## Simulated A/B Test Outcome

Offering tech support to non-users results in:
- Reduced churn probability (avg drop: ~0.1)
- ROI: **-44.98%** based on assumed costs and retention value (So, you know, not good. Would advice strategy team to make changes for this avenue)

## Tools & Libraries

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, SHAP

## Usage

1. Clone the repo  
2. Create and activate a virtual environment  
3. Install dependencies 

```bash
pip install -r requirements.txt
```
4. Run the notebook:  
```bash
jupyter notebook eda.ipynb
```

---

**Author**: Prabhu Kiran Avula
