# Diabetes Prediction with Explainable ML

Notebook-based implementation of diabetes prediction with model explainability.

## Notebook Pipeline

1. `1_Data_Preprocessing.ipynb`  
   - Data cleaning and feature engineering
   - Handling class imbalance with SMOTE
   - Train-test-validation split

2. `2_Model_Training.ipynb`  
   - XGBoost, Random Forest, LightGBM training
   - Hyperparameter tuning
   - Ensemble model creation

3. `3_Model_Evaluation.ipynb`  
   - Performance metrics calculation
   - ROC curves and confusion matrices
   - Feature importance analysis

4. `4_SHAP_Explanations.ipynb`  
   - Global SHAP feature importance
   - Local SHAP force plots
   - Dependence plots

5. `5_LIME_Explanations.ipynb`  
   - Local interpretable explanations
   - Feature contribution analysis
   - Multi-instance comparison

6. `6_Counterfactuals_Anchors.ipynb`  
   - DiCE counterfactual explanations
   - Anchor rule generation
   - What-if analysis

## Quick Start

1. Clone repo:
```bash
git clone https://github.com/yourusername/explainable-ml-diabetes.git
cd explainable-ml-diabetes