# Random Forest: Biome Classification and Regression

This project explores **Random Forest models** for biome classification and environmental regression using geographical data based on the Holdridge biome classification system. The trained model can be found in the notebook file 'name_of_notebook.ipynb' where a report of its performance can be found in [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22868415.svg)](https://doi.org/10.5281/zenodo.22868415) where we show how the training data was selected and the importance of the different features used in the model.

Here, we focus on training-data selection, feature analysis, and model evaluation. Different training regions and feature sets can be selected, allowing the performance of the classification models to be evaluated under different conditions. Random Forest regression is also used to predict environmental variables, with model performance assessed using appropriate evaluation metrics such as accuracy and mean squared error (MSE). This provides a flexible framework for investigating how data selection and feature composition influence model performance.

## Repository Contents

* **`BiomeData.zip`** — Contains the biome data, including the biome names and corresponding colors required for plotting and visualization.

* **`MulticlassBiomeClassifier.ipynb`** — Jupyter Notebook for retraining the multiclass biome classification model. The notebook allows users to select different regions for training and evaluates the performance of the resulting model.
