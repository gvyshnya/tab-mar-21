# Introduction
This repo will contain various EDA and ML experiments for Kaggle's [Mar 2021 Tabular Competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021).

# Files and Folders

- */data* subfolder contains the copy of the dataset of Kaggle's [Mar 2021 Tabular Competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021)
- *featurewiz-template-tps-mar2021.ipynb* - the starter featurewiz-related template for [Mar 2021 Tabular Competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021), kudos to Ram Seshadri, the original developer and primary contributor to/maintainer of *featurewiz* technology
- *Mar 21 TPC - Express EDA with AutoViz.ipynb* - the comprehensive EDA for the dataset, using [AutoViz](https://github.com/AutoViML/AutoViz), one of the popular Rapid EDA tools available in the market
- *Mar 21 TPC - Raw Feature Importance with Featurewiz.ipynb*
- *Mar 21 TPC - Advanced FE and FI with Featurewiz.ipynb*
- *kerasembeddings.ipynb* - the best category embedding experiment using Keras and all of the raw features in the dataset
- *kerasembeddings-lr00005.ipynb* - the category embedding experiment using Keras, all of the raw features in the dataset, and a smaller learning rate
- *kerasembeddings-without_noisy_cats.ipynb* - the category embedding experiment using Keras and a subset of original raw features (without the features detected as noisy/non-important by *featurewiz*)
- *lazypredict-models-screening.ipynb* - an experiment to quickly pre-screen the best ML algorithms to apply to the current classification problem, using *lazypredict* (*note: lazypredict* does not work with the modern neural network algorithms, and therefore it is limited to comparing the 'classical' ML algorithms supported by scikit-learn as well as the extension libraries providing the scikit-learn interface) 
- *lgbm-hyperopt.ipynb* - basic *lightgbm*-based ML experiment, with *lightgbm* params selected/tuned with *hypteropt*
- *lgbm-hyperopt-extreme-tr.ipynb* - the same as above, yet with the extrem training method applied for the best model tuned with *hypteropt* per the above
- *lgbm-xgb-catb-ensemble-hyperopt.ipynb* - the ensemble prediction (catboost, lightgbm, xgboost) with each model in the ensemble tuned with *hypteropt*
- *lightgbm-undesampling-hyperopt.ipynb* - the lightgbm ML experiment with undersampling (to balance the class labels in the target variable) and model tuning with *hypteropt*
- *tabularmarch21-dae-starter-cv-inference.ipynb* - the inherited DAE starter model 
- *tpg-mar2021-optuna-lgbm.ipynb* - the lightgbm-based ML experiment with the model params tuned with *optuna*
- *xgb-hyperopt.ipynb* - basic *xgboost*-based ML experiment, with *xgboost* params selected/tuned with *hypteropt*