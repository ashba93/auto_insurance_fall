# auto_insurance_fall

This repository contains Jupyter notebooks for a machine learning unbalanced binary classification task (Kaggle dataset).

The notebooks have:
  - "0. Preliminary XGBoost", a complete pipeline: data exploration, preprocessing, filling, correlations, fitting and predictions, classifications reports, shap analysis.
  - "1. Preprocessing": preprocessing data and saving preprocessed data.
  - "2. Models": logistic regression, random forest, xgboost and catboost models are trained.
  - "3. Ensemble": a stacking classifier of the models is trained.
  - "4. Write predictions": create a csv of predictions on test set.


Inside the folder "/data-scientist-technical-test-main/data/auto-insurance-fall-2017/" , there are:
  - "train_auto_preproc.csv", "test_auto_preproc.csv": the preprocessed files.
  - "LR.pkl", "RF.pkl", "XGB.pkl", "CBC.pkl", "Ensemble.pkl": the fitted models.
  - "predictions.csv": the predictions on test set.

The libraries used are those inside the requirements.txt file.
