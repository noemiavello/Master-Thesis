# Master Thesis: "Using Shapley Values for Assessing Feature Importance in Insurance Prediction Models"

This project involves the data set and application codes for the master thesis. The key components include:

* **Data Set**: The dataset used for this project.
* **Data Manipulations**: Relevant data manipulations.
* **Machine Learning Models**: Implementation of various machine learning models.
* **SHAP Application**: Application of Shapley Additive explanations (SHAP) for model interpretability.

All development and analysis were conducted in Google Colab.

## Getting Started

### Data

The frenchclaim.csv file contains the French motor third-party liability (MTPL) claims data set, also available through the R library CASdatasets (freMTPL2freq).

### Accompanying Code
The following Python notebooks are provided in the order to run:

* **p01_data_prep.ipynb**: Python notebook detailing the exploration data analysis and data manipulation. 
* **p02_1-GLM_SHAP.ipynb**: Python notebook detailing the data modeling applying the generalized linear model and SHAP analysis using Kernel SHAP.
* **p02_2-DNN_SHAP.ipynb**: Python notebook detailing the data modeling applying the deep neural network model and SHAP analysis using Deep SHAP.
* **p02_3-RF_SHAP.ipynb**: Python notebook detailing the data modeling applying the random forest model and SHAP analysis using Tree SHAP.
* **p02_4-TrueModel_SHAP.ipynb**: Python notebook detailing the data modeling and the true model function to apply SHAP analysis using Kernel SHAP.

### Installing

* !pip install glum for the generalized linear model 
* !pip install shap for SHAP
* !pip install Tensorflow==2.8.0 use this version for Tensorflow 


## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

