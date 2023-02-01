# Diagnosing the Risk of Heart Disease using Deep Learning

#### -- Project Status: Completed

## Project Objective
Make the best deep neural network model with hypertuning to carry out the classification process of detecting people having or not having heart disease. Then, do analysis on accuracy, precision, recall and, f1-score of the model.

### Methods Used
* Deep Learning
* Neural Network

### Language
* Python

### Module
* Pandas
* Matplotlib
* Numpy
* Seaborn
* Keras
* Tensorflow
* Sklearn


## Step-by-step
1. Dataset analysis
2. Cleaning data
    * Handle missing values
    * Handle duplicates data
    * Hanlde the outliers
3. Data Visualization
4. Sampling data
    * The data is quite balanced, no need for over/undersampling
6. Data preparation
    * Train-test-val split with the proportion 8:1:1
7. Tuning hyperparameter
Using Hyperparameter Tuning, we got
    * Best number of layer  : 3
    * Best number of neuron : 300
8. Build the model
9. Model evaluation
    * Precision : 0.83
    * Recall    : 0.79
    * F1-score  : 0.80
    * Accuracy  : 81%

## Getting Started
1. You can access the raw data [here](https://github.com/angelpatriciads/risk-heart-disease/blob/main/heart_dataset.csv) within this repo.
2. All of the scripts are being kept [here](https://github.com/angelpatriciads/risk-heart-disease/blob/main/risk_heart_disease.ipynb).
