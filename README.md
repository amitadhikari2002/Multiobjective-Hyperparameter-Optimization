# DE-NSGA-III Hyperparameter Optimization

A hybrid multiobjective optimization framework integrating **NSGA-III** and **Differential Evolution (DE)** for hyperparameter optimization of deep learning models.

## Overview

This project proposes **DE-NSGA-III**, a hybrid evolutionary algorithm that combines the diversity preservation of NSGA-III with the fast convergence of Differential Evolution. The framework is applied to optimize the hyperparameters of a Multi-Layer Perceptron (MLP) trained on the MNIST dataset.

## Features

- Hybrid DE-NSGA-III algorithm
- Multiobjective hyperparameter optimization
- Pareto-front based solution selection
- MLP implementation using TensorFlow/Keras
- Evaluation on the MNIST dataset

## Objectives

- Maximize Classification Accuracy
- Maximize F1-Score
- Minimize Model Complexity

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Evolutionary Algorithms
- NSGA-III
- Differential Evolution

## Results

- Improved Accuracy
- Improved F1-Score
- Faster convergence compared to standard NSGA-III
- Better Pareto-optimal solutions

## Repository Structure

```
├── src/
├── notebooks/
├── results/
├── figures/
├── README.md
└── requirements.txt
```

## References

- Deb et al. (2002) – NSGA-II
- Deb & Jain (2014) – NSGA-III
- Differential Evolution
