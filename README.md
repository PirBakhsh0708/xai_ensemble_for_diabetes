**Towards Reliable and Transparent Diabetes Diagnosis with an Explainable Ensemble Framework for Clinical Decision Support**

Notebook-based implementation of diabetes prediction with model explainability.

## Notebook Pipeline

1. Data_Preprocessing 
   - Data cleaning and feature engineering
   - Handling class imbalance with SMOTE
   - Train-test-validation split

2. Model_Training  
   - XGBoost, Random Forest, LightGBM training
   - Hyperparameter tuning
   - Ensemble model creation

3. Model_Evaluation 
   - Performance metrics calculation
   - ROC curves and confusion matrices
   - Feature importance analysis

4. SHAP_Explanations  
   - Global SHAP feature importance
   - Local SHAP force plots
   - Dependence plots

5. LIME_Explanations  
   - Local interpretable explanations
   - Feature contribution analysis
   - Multi-instance comparison

6. `6_Counterfactuals_Anchors  
   - DiCE counterfactual explanations
   - Anchor rule generation
   - What-if analysis

## Quick Start

1. Clone repo:
```bash
git clone https://github.com/yourusername/explainable-ml-diabetes.git
cd explainable-ml-diabetes
