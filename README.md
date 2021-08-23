# NTCP modelling in head-and-neck cancer

Notebooks for modelling Normal Tissue Complication Probability in head-and-neck cancer patients undergoing radiotherapy.

1. [Data cleaning](data_cleaning.ipynb): Combine data from json and csv files into pandas DataFrame, clean up columns, and compute additional features.
2. [Model validation](model_validation.ipynb): Apply published models to the data and compare performance with published performance. Use synthetic data to investigate discrepancies.
3. [Model building](model_building.ipynb): Attempt to build NTCP models from scratch with scikit-learn. Compare logistic regression, KNN, SVM, random forest, BDT.
