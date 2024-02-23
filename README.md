# README.md

This project contains Jupyter Notebooks for processing and analyzing communication data and outcomes for B2B business opportunities. 

Two Notebooks are of highest interest:

- `Data Processing.ipynb` - provides a deep dive into data, how it can be aggregated and put together
- `Model Training.ipynb` - provides the code for data normalization, additional feature engineering, and model training. Additionally, select metrics are calculated and plots created so that model comparison can be conducted.
- `SHAP Intepretation.ipynb` - provides SHAP explanations for the SVC and LGBM models on the aggregate and singular levels. Additionally, estimates the financial effects of using the model within the two context described in the main text.

In addition, the `src` folder contains raw data, and the `model` table contains the current best set of models. 

Other files are temporary artifacts that might not be stable and should not be used for analysis. They will likely be removed in future commits.