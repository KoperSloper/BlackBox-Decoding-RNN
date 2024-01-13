# Decoding the Black Box: Stock Return Prediction with RNNs

This repository contains the code for my thesis project, which explores the interplay of input variables, hidden states, and neurons in stock return prediction using Recurrent Neural Networks (RNNs).

## Repository Contents

- **Data**: `dataset_final.xlsx`
- **Model**: `LSTM_[256, 512, 256, 128]_val_loss_0.09.pth` - This is the optimal model with the best hyperparameters.
- **Notebooks**:
  - `data, training, evaluation, ig, conductance.ipynb` - This notebook contains the majority of the work including data preparation, model training, and evaluation.
  - `IG_twocases.ipynb` - This notebook explores integrated gradients for positive and negative predictions.
  - `performance_metrics.ipynb` - This notebook shows how the performance metrics are calculated.

## Project Overview

The code in this repository demonstrates how the data is prepared, how the model is trained, and how the optimal hyperparameters and final model are chosen. It also delves into the interpretability aspects of the model, providing insights into the complex relationships between input variables, hidden states, and neurons.

## Requirements

To run this code, you will need the following Python libraries:

- PyTorch
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Ray
- Statsmodels.api
- Captum
