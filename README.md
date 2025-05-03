# Robust Value Iteration (RVI)

This repository contains an implementation of Robust Value Iteration (RVI) for safe autonomous decision-making in uncertain environments. The algorithm adapts the reward signal based on estimated state-transition uncertainty.

## File

- `RVI.ipynb`: Main Jupyter notebook implementing RVI with clustered state abstraction and beta-uncertainty weighting.

## Overview

- **Robust MDPs**: Solve Markov Decision Processes with robustness to transition uncertainty.
- **State Clustering**: Use KMeans to reduce dimensionality of the state space.
- **Uncertainty Estimation**: Train a logistic regression model to estimate transition reliability.
- **Beta Scaling**: Dynamically adjust rewards based on transition uncertainty.

## Requirements

Make sure you have the following packages installed:

```bash
pip install numpy scikit-learn matplotlib gym highway-env
