# Apprenticeship Completion Risk Modelling

## Overview

This project predicts whether an apprentice is likely to overrun their expected completion timeline using early engagement and learner data.
The goal is to enable early intervention and improve completion outcomes.

## Problem Framing
Originally modelled as a regression problem (predicting total days on programme), the project was reframed into a binary classification task:
"Will this learner complete on time or overrun?"
This shift improves business actionability and intervention targeting.

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
Tree-based models perfomed best, with behavioural engagement features providing the strongest predictive signal.

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
4. Run [script](Learner-Completion-Modelling.ipynb) in Jupyter Notebook or Google Colab.
