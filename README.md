# BMIF 802 - Lab 6: Classification Models

## Description

In this lab, you use the real Cleveland Heart Disease dataset to build a binary classification workflow. The lab begins with data inspection and preprocessing, then compares k-nearest neighbours, a decision tree, and a random forest. It also examines the effect of standardization on k-NN and uses a training/testing split and 5-fold cross-validation to compare models.

## Learning objectives

By the end of the lab, you should be able to:

- prepare a medical dataset for classification
- identify and handle missing values
- convert coded categorical variables into model-ready features
- create stratified training and testing sets
- explain why feature scaling matters for k-NN
- train k-NN, decision tree, and random forest classifiers
- use accuracy and cross-validation results to compare models
- recognize overfitting and discuss interpretability, bias, fairness, and clinical limitations

## Packages

The lab uses:

- `pandas`
- `matplotlib`
- `scikit-learn`

## Checklist

- [ ] Read `DATASET_DESCRIPTION.txt`.
- [ ] Open `Lab_06_Classification.ipynb`.
- [ ] Load and inspect the dataset.
- [ ] Create the binary target column.
- [ ] Split the data before learned preprocessing steps.
- [ ] Handle missing values using information from the training data.
- [ ] Transform the categorical predictor columns.
- [ ] Calculate a baseline accuracy.
- [ ] Compare unscaled and standardized k-NN models.
- [ ] Choose a value of `k` using 5-fold cross-validation.
- [ ] Train a decision tree and inspect its structure.
- [ ] Train a random forest.
- [ ] Compare training, testing, and cross-validation accuracy.
- [ ] Complete the interpretation and AI-consideration questions.

## Dataset source

The data is the processed Cleveland subset of the UCI Heart Disease dataset:

Janosi, A., Steinbrunn, W., Pfisterer, M., & Detrano, R. (1989). *Heart Disease* [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C52P4X
