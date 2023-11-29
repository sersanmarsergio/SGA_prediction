# SGA_prediction
 Prediction of small for gestational age from fetal ultrasound and clinical characteristics: a comparative study between a low-middle-income and a high-income country

How to approach this project: 


launchClassificationModels.ipynb: This notebook loads train/test dataset from FEDOC and IMPACT (clinical data, biometry, and echo Doppler measurements, in isolation or using a combination of them) and launches XGBoost (implementing 5-fold CV and Bayesian hyperparameter optimization) to predict an array of adverse perinatal outcomes. It also provides ROC curves and classical classification scores (sensitivity, specificity, PPV, NPV) as well as SHAP values to interpret the model's meaning.