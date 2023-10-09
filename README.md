Wine Quality Prediction Using Machine Learning
This repository contains Python code for a machine learning project that predicts the quality of wine using various machine learning algorithms, with a focus on data exploration, preprocessing, and classification.

Dataset
The dataset used in this project is the "Wine Quality" dataset, which includes features related to wine properties and wine quality scores.

Data Source
You can find the dataset used in this project here: Wine Quality Dataset

Code Overview
Exploratory Data Analysis (EDA)
The project starts with exploratory data analysis (EDA) to understand the dataset.
Box plots and distribution plots are created to visualize data distributions and identify outliers.
Log transformation is applied to specific columns to handle skewed data.

Data Preprocessing
Data preprocessing steps include handling categorical data and performing oversampling using SMOTE to address class imbalance.
Categorical columns such as 'type' and 'quality' are transformed for modeling.
The dataset is split into input features (X) and target variable (y) for classification.
Model Classification
Various machine learning models are implemented and evaluated for wine quality prediction.
The following models are used:
Logistic Regression
Random Forest Classifier
Extra Trees Classifier
XGBoost Classifier
LightGBM Classifier
Model Evaluation
Model accuracy and cross-validation scores are reported to assess model performance.
The classification results are displayed for each model.

Prerequisites
Python

Jupyter Notebook/Google Colab

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost, imbalanced-learn, lightgbm

Contribution
Contributions are welcome! If you'd like to contribute to this project or suggest improvements, please feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.



