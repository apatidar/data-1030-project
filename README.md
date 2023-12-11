# data-1030-project

Title: Time-Series Forecasting of Crime in Los Angeles, California

Los Angeles, the second most-populous city in the country, experiences a broad spectrum of urban crime. This analysis aims to understand historical crime trends and employ regression techniques to forecast future criminal activity, a problem that has not been previously addressed in this context. The objective of this research is to facilitate a deeper understanding of crime patterns in the city, enabling more informed resource allocation by law enforcement to improve public safety.

The dataset was sourced from Kaggle but originally retrieved from the Open Data repository maintained by the City of Los Angeles. It encompasses manually-transcribed crime reports spanning from January 2010 to April 2023.

Dataset: https://www.kaggle.com/datasets/chaitanyakck/crime-data-from-2020-to-present

Please note that the dataset was too large to store on GitHub!

Packages:

channels:
- conda-forge
- defaults
dependencies:
- python=3.11.4
- matplotlib=3.7.2
- seaborn=0.12.2
- pandas=2.0.3
- scikit-learn=1.3.0
- numpy=1.24.4
- py-xgboost=1.7.6
- shap=0.42.1
- jupyterlab=3.6
- plotly=5.8.0
- ipywidgets=7.7.0
