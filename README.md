# Random Forest: Biome Classification and Regression

This project explores **Random Forest models** for biome classification and environmental regression using geographical data based on the Holdridge biome classification system. The trained model can be found in the notebook file 'name_of_notebook.ipynb' where a report of its performance can be found in [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22868415.svg)](https://doi.org/10.5281/zenodo.22868415) where we show how the training data was selected and the importance of the different features used in the model.

The project includes binary and multi-class biome classification, with careful training-data selection and feature analysis. In one case, a multi-class model achieved approximately **85% global accuracy**, while a model trained on a less representative region achieved **54%**, demonstrating the importance of data selection. Random Forest regression was also used to predict environmental variables, achieving approximately **96% accuracy** for vegetation carbon pool prediction and an **MSE of 0.0005** for NPP prediction.

## Repository Contents

* **`BiomeData.zip`** — Contains the biome data, including the biome names and corresponding colors required for plotting and visualization.

* **`MulticlassBiomeClassifier.ipynb`** — Jupyter Notebook for retraining the multiclass biome classification model. The notebook allows users to select different regions for training and evaluates the performance of the resulting model.
