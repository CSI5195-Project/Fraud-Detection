# Examining Fairness in CSNN-based Fraud Detection through Explainability

The following repository contains the source code for producing the project results. It includes extensions of the source code produced by D. Perdig˜ao et al. in the paper: 

Perdigão, D., Antunes, F., Silva, C., & Ribeiro, B. (2025). Improving Fraud Detection with 1D-Convolutional Spiking Neural Networks Through Bayesian Optimization. In M. F. Santos, J. Machado, P. Novais, P. Cortez, & P. M. Moreira (Eds.), Progress in Artificial Intelligence (pp. 127–138). Cham: Springer Nature Switzerland.

The dataset used is available at: https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022. Filepaths for the dataset and imported modules need to be adjusted accordingly. 

_/src_ contains the code for running the three models.

It includes a subfolder specific to each model. 

The four files in the /src directory contain utility functions and variables that need to be imported in each of the model-specific notebooks. 

_/analysis_ contains the notebooks for producing the Explainability results using SHAP and LIME
