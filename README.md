# FairFace Gender Bias Analysis

## Overview
This notebook demonstrates gender classification on the FairFace dataset using a ResNet50 base model. It includes data loading, exploratory data analysis (EDA), model training, evaluation, and fairness metric calculations by race to assess potential bias in classification.

## Features
- Download and preprocess the FairFace dataset.
- Visualize race and gender distributions.
- Train a baseline ResNet50 model for binary gender classification.
- Evaluate the model with classification reports, confusion matrices, ROC curves.
- Assess fairness using metrics like accuracy, selection rate, and false positive rate by race groups.
- Save trained model and visualization plots.

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- TensorFlow / Keras
- scikit-learn
- Fairlearn
- AIF360
- pandas, seaborn, matplotlib

## How to Use
1. Clone or download the repository.
2. Open `fairface-gender-bias-analysis.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells sequentially to reproduce the data processing, training, evaluation, and fairness analyses.
4. Explore saved plots and model artifacts in the working directory.

## Status
This notebook is organized and cleaned for clear presentation on GitHub.