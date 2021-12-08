# INF 554 Machine and Deep Learning
# Data Challenge: H-index Prediction
**Team: Good To Go**
* Gurami KERETCHASHVILI
* Guillaume BARTHE
* Temur MALISHAVA 


# Description
The goal of this data challenge is to study and apply machine learning/artificial intelligence techniques to a real-world regression problem. In this regression problem, each sample corresponds to a researcher (i. e., an author of research papers), and the goal is to build a model that can predict accurately the h-index of each author.


# Getting started
## Requirements

To install the requirements, run at the root folder:

> ```pip install -r requirements.txt```

## Required files

All the original data files must be located in the same directory as the coding files which is in the ```code``` folder.
The data can be found on the website: https://www.kaggle.com/c/inf554-2021/data.

## Run the model

First, with the code in Part1_GTG.ipynb notebook you can run the data preprocessing of the data, feature extraction and feature selection. As a result this notebook creates two files, train_data_cleaned.csv and test_data_cleaned.csv, which will be used later in the Part2_GTG.ipynb and Part3_GTG.ipynb.

In the Part2_GTG.ipynb notebook we perform an analysis of the data and build baseline models for the simplest regressors to see the differences between them.

Finally, the Part3_GTG.ipynb notebook builds our neural network model, trains it, and validates the results. This notebook uses already cleaned versions of the datasets, train_data_cleaned.csv and test_data_cleaned.csv, and it performs a prediction to upload on kaggle.


