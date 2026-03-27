# Multilayer Perceptron: Depth, Width and Activation Functions

## Overview

This project explores how different design choices affect the performance of a Multilayer Perceptron (MLP) on a binary classification task.

The focus is on three main factors:

* Depth (number of hidden layers)
* Width (number of neurons)
* Activation functions

---

## Objective

The aim is to understand how changing these parameters impacts model accuracy and to identify the best configuration.

---

## Dataset

* Synthetic dataset created using sklearn
* 1000 samples
* 20 features (15 informative)
* Binary classification

Preprocessing:

* 80/20 train-test split
* StandardScaler used for feature scaling

---

## Experiments

### Depth

* Tested models with 1 to 4 hidden layers
* Best result: 1 layer (94%)
* Increasing depth reduced performance

### Width

* Tested 10, 30, 50, 100, 150 neurons
* Best result: 100 neurons (95.5%)
* Too few neurons caused underfitting
* Too many gave little improvement

### Activation Functions

* Tested ReLU, Tanh, Logistic

Results:

* Tanh: 95% (best)
* ReLU: 92.5%
* Logistic: 85.5%

---

## Key Findings

* Shallow networks performed better for this task
* Increasing width improved performance up to a point
* Tanh activation worked best
* Logistic activation performed poorly

---

## How to Run

1. Install requirements:
   pip install -r requirements.txt

2. Run notebook:
   jupyter notebook notebook.ipynb

---

## Files

* notebook.ipynb → code
* tutorial.pdf → report
* README.md → project description

---

## References

* https://scikit-learn.org/stable/modules/neural_networks_supervised.html
* Goodfellow et al. (2016)
* Nielsen (2015)
* Brownlee (2020)
* Bishop (2006)

---

## Submission

This repository is part of coursework submission.

Add your GitHub link here.
https://github.com/ds25abd/24135630_project
