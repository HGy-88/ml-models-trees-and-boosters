# Multi-Class Prediction of Obesity Risk (EDA, FE, ML)                                                                                                                        
[![CodeFactor](https://www.codefactor.io/repository/github/hrczggyrgy/ml-models-trees-and-boosters/badge)](https://www.codefactor.io/repository/github/hrczggyrgy/ml-models-trees-and-boosters)
End-to-end approach for predicting multi-outcome variable

# Multi-Class Prediction of Obesity Risk

## Notebook: [GitHub link](https://github.com/HGy-88/ml-models-trees-and-boosters/blob/9b37b4cefd1cc23fc3d4bd91ca13d4212bdcf9bf/multi-class-prediction-obesity-eda-fe-ml.ipynb)

## Description
This project focuses on the multi-class prediction of obesity risk in individuals, a factor closely related to cardiovascular diseases. Utilizing machine learning techniques, the analysis is performed on a dataset generated from a deep learning model trained on the Obesity or CVD risk dataset. This project aims to identify and analyze various contributing factors to predict obesity risk accurately.

### Insights and Assumptions
The dataset offers insights into factors influencing obesity, including family history, dietary habits, physical activity, hydration, and lifestyle choices like smoking and alcohol consumption. It acknowledges assumptions regarding the accuracy of self-reported data, the static nature of data snapshots, generalization to broader populations, and the distinction between correlation and causation

## Features
Comprehensive Data Analysis: Includes EDA, feature engineering (FE), and model evaluation using advanced algorithms.
Machine Learning Models: Utilizes RandomForest, XGBoost, LightGBM and more, with hyperparameter tuning via Optuna. Final tuned ensembled model trained on Kaggle TPU-s.

## Dataset
The dataset includes training and test data, closely mimicking the feature distributions of the original Obesity or CVD risk dataset but generated through deep learning techniques to ensure diversity and complexity in data analysis.

- **Type:** csv
- **License:** Attribution 4.0 International (CC BY 4.0)
- **Source:** [Kaggle Competition](https://www.kaggle.com/competitions/playground-series-s4e2)

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Installation
1. Clone the repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
Running the Project
Open the Jupyter Notebook (EDA_PREDA.ipynb) in JupyterLab or Notebook.
Execute the cells sequentially to perform the exploratory data analysis and subsequent model training and evaluation.
License
This project is open-sourced under the Attribution 4.0 International (CC BY 4.0) license.

Acknowledgments
Dataset provided by Kaggle.
