# Multi-Layer Perceptron

* `Assignment 4 - MLP.ipynb`: which is a notebook contains the implementation of several version of MLP model, including the baseline model and the improved ones
* `winequality-red.csv`: the dataset, also available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality), at [Kaggle](https://www.kaggle.com/datasets/sh6147782/winequalityred), etc.

## Structure of the notebook
1. The EDA.
2. Transforming the data, including training, testing, and validation split, transforming the data to fit in pytorch dataloader.
3. Creating the baseline model and configuring.
4. Three improved versions of the model: (1)data normalizing (improve by 12%), (2)number of the unit in the hidden layer decreased to 3 (improve by 11%), (3)number of the unit in the hidden layer decreased to 2 (deteriorate by 4%)
