# Early Risk Prediction for Apprenticeship Completion

## Business Problem

Late completions create operational strain, reduce funding predictability, and limit intervention capacity.

This project builds a model to identify, within the first 90 days, which learners are at risk of overrunning their programme timeline.

## Approach
* Data cleaning and preprocessing
* Feature engineering from early engagement metrics
* Scikit-learn Pipelines with ColumnTransformer
* Train/test split with cross-validation

## Evaluation
Metrics used:
* ROC-AUC
* Precision/Recall
* F1 Score
* Confusion Matrix

## Business Application
This model could:
* Trigger early intervention workflows
* Improve completion rates
* Support operational forecasting
* Optimise support resource allocation

## Tech Stack
* Python
* Pandas & NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## Getting Started
1. Clone this repository. 
2. Create virtual environment.
3. Install [requirements](requirements.txt).

   `pip install -r requirements.txt`
4. Run [script](Learner-Completion-Modelling.ipynb) in Jupyter Notebook or Google Colab.
