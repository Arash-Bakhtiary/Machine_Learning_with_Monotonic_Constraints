# Machine Learning with Monotonic Constraints for Maintenance Cost Prediction

## Overview

This repository demonstrates the use of **machine learning models** with **monotonic constraints** to predict maintenance costs. It features a comparison between traditional **linear regression** and **CatBoost** with monotonic constraints, highlighting how monotonic constraints can improve both model performance and interpretability, especially in real-world business applications such as **maintenance cost prediction**.

### Key Features
- **Monotonic Constraints**: Enforces a monotonic relationship between maintenance level and maintenance costs, where the cost increases as the maintenance level rises.
- **CatBoost Model**: Demonstrates how CatBoost’s monotonic constraints can capture non-linear but monotonic relationships.
- **Linear Regression Comparison**: Highlights the limitations of linear regression in modeling non-linear relationships, where a monotonic constraint is more suitable.
- **Synthetic Data**: Simulates maintenance data, illustrating how models handle realistic, non-linear increases in cost based on maintenance levels.
- **Visualization**: Provides plots comparing the performance of linear regression and CatBoost models to showcase the impact of monotonic constraints.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this notebook, you will need the following Python packages:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `catboost`

You can install them via pip:

```bash
pip install numpy pandas scikit-learn matplotlib catboost
