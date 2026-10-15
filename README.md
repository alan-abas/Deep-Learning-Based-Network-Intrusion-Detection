
# Deep Learning-Based Network Intrusion Detection

## Project Overview

This project aims to develop a machine learning system that classifies network traffic as benign or malicious.

The project will use labeled network traffic data to train and evaluate deep learning models for network intrusion detection.

## Objectives

- Prepare and analyze a network traffic dataset.
- Build a baseline Artificial Neural Network (ANN).
- Compare the ANN with a 1D Convolutional Neural Network (1D-CNN), if feasible.
- Evaluate models using accuracy, precision, recall, F1-score, and a confusion matrix.
- Explore SHAP to explain model predictions, if feasible.
- Avoid data leakage and document limitations.

## Technologies

- Python
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Jupyter Notebook
- TensorFlow or PyTorch (to be selected later)
- SHAP (planned)

## Project Structure

- `docs/` - Project documentation and research notes.
- `data/` - Datasets and processed data; excluded from Git.
- `src/` - Python source code.
- `models/` - Trained model files.
- `results/` - Evaluation metrics and charts.
- `tests/` - Tests.
- `requirements.txt` - Core Python dependencies.

## Current Status

Environment setup and initial project structure are in progress.

Dataset preparation, model development, and evaluation have not started.

## Scope and Limitations

The initial system will classify labeled network traffic. It will not perform live network monitoring or automatically block traffic.

Model performance and explainability will be reported based on actual experiments, not assumed results.
