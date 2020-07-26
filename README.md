# machine-learning-challenge

## Background
This project explores different machine learning models to determine which may be best to identify exoplanets from NASA data.

This repository contains three Jupyter notebooks—one per model with the exception of the linear regression model also found [here](https://github.com/sahobitayo/machine-learning-challenge/blob/master/decision%20_tree.ipynb) and copy of the source data in CSV format. If you'd like to experiment with these notebooks, simply git clone or download this repo to a computer that has pandas, scikit-learn, and Jupyter installed.

## Preparing Models
- Determined feature importances by running Decision Tree and Random Forest models. The features that showed the most promise were: `koi_fpflag_co`, `koi_fpflag_nt`, `koi_fpflag_ss`, `koi_model_snr`, `koi_prad`, `koi_prad_err2`, `koi_duration_err2`.
- Used the features to train the K Nearest Neighbors and SVC models.
- Used `GridSearchCV` to hypertune the models and boost performance.
- Tested the models (adding and removing features, running model with and without GridSearchCV) to confirm that feature selection was appropriate.

## Model Performance



### Data Source
https://www.kaggle.com/nasa/kepler-exoplanet-search-results


### Tools Used
- **Python**
- **Pandas library**
- **Jupyter Notebook**
- **Matplotlib library**
- **sklearn library**

