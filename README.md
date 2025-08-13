# Bayesian Logistic Regression for Liver Cirrhosis Survival Prediction

This project applies **Bayesian logistic regression** to a clinical dataset on liver cirrhosis survival outcomes.  
The analysis investigates the effect of clinical, demographic, and biochemical variables on patient mortality using  
rigorous model specification, prior selection, and performance evaluation.

## 📊 Project Overview
- **Goal**: Identify key predictors of mortality in liver cirrhosis patients
- **Dataset**: 418 records, 17 clinical variables (Kaggle)
- **Outcome**: Binary (Survived = 0, Death = 1)

## 🛠 Methods
- Bayesian logistic regression (`brms` in R)
- Prior specification and sensitivity analysis
- Leave-One-Out Cross-Validation (`loo`) for model comparison
- Sensitivity & specificity analysis on hold-out data
- Data preprocessing: one-hot encoding, standardization, feature engineering

## 🧰 Tools & Libraries
- R, `brms`, `loo`, `ggplot2`, `corrplot`, `caret`, `synthpop`
- LaTeX for scientific reporting

## 📈 Key Results
- Top predictors: bilirubin, age, alkaline phosphatase, ascites, edema
- Best-performing model: Specificity ~77%, Sensitivity ~65%
- Priors and model complexity impacted performance and interpretation

## 📄 Full Report
[Download PDF](https://raw.githubusercontent.com/mohaiminul-git/Bayesian-Logistic-Regression-for-Liver-Cirrhosis-Survival-Prediction/main/Bayesian-Logistic-Regression-for-Liver-Cirrhosis-Survival-Prediction.pdf)

## 🔑 Skills Demonstrated
- Bayesian statistical modeling
- Medical data preprocessing and visualization
- Model diagnostics and evaluation
- Collaborative academic project execution
