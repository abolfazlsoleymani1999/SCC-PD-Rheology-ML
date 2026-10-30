# SCC-PD-Rheology-ML
Data and Python code for predicting SCC rheology using Packing Density and Machine Learning

# Data and Code for: Predicting SCC Rheology using Packing Density and ML

This repository contains the dataset and Python code used in the study:
**"Linking Packing Density to Self-Consolidating Concrete Rheology: Experimental Evidence and Machine Learning Models"**

## Contents
- `Data/Data.csv`: The complete dataset (experimental and literature data).
- `Code/finalcode(3).ipynb`: Jupyter notebook for data preprocessing, ML modeling (SVR, KRR, ETR), sensitivity analysis, and ablation analysis.

## Requirements
The code is written in Python 3.x. Required libraries:
- numpy
- pandas
- scikit-learn
- matplotlib
- shap (for SHAP analysis)

## Usage
1. Clone the repository.
2. Place `Data.csv` in the same directory as the notebook (or adjust the path in the code).
3. Run the Jupyter notebook cell by cell.
