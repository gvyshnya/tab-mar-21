# Introduction
This repo will contain various EDA and ML experiments for Kaggle's [Mar 2021 Tabular Competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021).

# Files and Folders

- */data* subfolder contains the copy of the dataset of Kaggle's [Mar 2021 Tabular Competition](https://www.kaggle.com/c/tabular-playground-series-mar-2021)
- *Mar 21 TPC - Express EDA with AutoViz.ipynb* - the comprehensive EDA for the dataset, using [AutoViz](https://github.com/AutoViML/AutoViz), one of the popular Rapid EDA tools available in the market
- *kerasembeddings.ipynb* - the best category embedding experiment using Keras and all of the raw features in the dataset
- *kerasembeddings-lr00005.ipynb* - the category embedding experiment using Keras, all of the raw features in the dataset, and a smaller learning rate
- *kerasembeddings-without_noisy_cats.ipynb* - the category embedding experiment using Keras and a subset of original raw features (without the features detected as noisy/non-important by *featurewiz*)
- *lazypredict-models-screening.ipynb* - an experiment to quickly pre-screen the best ML algorithms to apply to the current classification problem, using *lazypredict* (*note: lazypredict* does not work with the modern neural network algorithms, and therefore it is limited to comparing the 'classical' ML algorithms supported by scikit-learn as well as the extension libraries providing the scikit-learn interface) 
- *lgbm-hyperopt-extreme-tr.ipynb*
- *lgbm-hyperopt.ipynb*
- *lgbm-xgb-catb-ensemble-hyperopt.ipynb*
- *lightgbm-undesampling-hyperopt.ipynb*
- *tabularmarch21-dae-starter-cv-inference.ipynb*
- *tpg-mar2021-optuna-lgbm.ipynb*
- *xgb-hyperopt.ipynb*