# NeonatalPathologies

## Description

This project is an engineering thesis to analyze and implement two different scenarios related to the use of machine learning in predicting the development of neonatal pathology. The repository contains documentation in the form of the engineering thesis, code and results. The dataset was provided by the Neonatology Clinic of the Jagiellonian University Medical College, consisting of laboratory blood tests and cardiac hemodynamic studies of the clinic’s patients. The data was first reviewed. Values were extracted from the images and combined with the provided dataset. Subsequently, after consultation with doctors, the features to be used for the study were selected. After that, the collection was divided according to the recommendations into two neonatal scenarios. After the split, blemished samples were removed or modified. Then, with the division into scenarios, specific machine learning models (focusing mainly on shallow learning models) were learned for parameter prediction. The results for each model are shown in graphs and tables. The study conducted has allowed providing clues to predict parameters for both Scenario 1 - Echo-Cardiological Prediction and Scenario 2 - Predicting Newborn Development. The results suggest that further work could lead to more precise models despite the fact that the current ones have not reached full effectiveness. This is particularly evident in Scenario 1, where the predicted values for the left and right ventricles are good enough that they could potentially be implemented to help physicians in the near future.

## Structure
* `model_ver1`: Scenario 1 - Echo-Cardiological Prediction
* `model_ver2`: Scenario 2 - Predicting Newborn Development
* `results/`: folder containing results for both scenarios for Linear Regression, KNN, Random Forest, Gradient Boosting, MLP, Isolation Forest models

## Requirements

To run the models, the following libraries are required:

`pip install -r requirements.txt`

## Execution

To run the analysis, open the appropriate Jupyter Notebooks and execute the code cells sequentially.

`jupyter notebook`
