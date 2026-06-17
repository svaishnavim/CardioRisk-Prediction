# CardioRisk-Prediction
Problem Statement:  Develop a predictive model for cardiovascular disease risk helping to simplify the early stages of patient assessment. Instead of relying solely on time-consuming consultations and manual checks, a screening model can highlight individuals who may need quicker attention.

Tasks:
- Data Understanding
  - Remove irrelevant columns
- Data Cleaning
  - Identify & handle redundant/invalid/illogical physiological values
  - Fix data types
- EDA
  - Perform univariate analysis
  - Perform correlation analysis
  - Perform bivariate analysis
- Train-Test Split
 - Define feature & target(s) variable(s)
 - Split data into training and validation sets
- Feature Engineering
  - New feature creation
  - Combine values in categorical columns
  - Dummy variable creation
  - Feature rescaling
- Model Building
  - Build linear SVM and find optimal cutoff
  - Build simple decision tree and find optimal cutoff
  - Hyperparameter tuning
- Predictions & Model Evaluation
  - Make final predictions and evaluate
- Report
  - Exploratory data analysis and feature engineering
  - Model building & hyperparameter tuning
  - Model cards, final insights and conclusions

Python libraries used:
- pandas
- matplotlib
- scikit-learn
- warnings
- joblib (to save where required)
- random
- seaborn
