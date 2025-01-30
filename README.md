# NAXIVA

Machine learning model with Logistic Regression and leave-one-out cross validation approach,
  integrating results from the NAXIVA Phase II clinical trial to find the most predictive
  biomarkers for this cohort of patients.
  
  Software dependencies:
  numpy (v2.0.2)
  pandas (v2.2.3)
  scikit-learn (v1.5.2)
  jupyter (v1.1.1)
  
  Two models are presented:
  - Baseline model (week 1 features)
  - Dynamic model: baseline features (week 1) + dynamic features (fold-change features between week 1 and week 3)
  
  For each model, run the relevant script, where the relevant data is in the 'NAXIVA_data' folder. The "results" csv contains the results for each leave-one-out iteration, with a list of the features selected in the feature reduction step and the weights assigned to each feature by the logistic regression model.

  Publication:
  - R Wray, H Paverd et al. Angiogenic and Immune Predictors of Neoadjuvant Axitinib Response in Renal Cell Carcinoma with Venous Tumour Thrombus (2025).
