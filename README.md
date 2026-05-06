# Fashion MNIST Classification Project

This project implements a machine learning classification flow on the Fashion-MNIST dataset.

## Project Goal
Classify clothing images into 10 categories using a supervised learning model.

## Dataset
The dataset used in this project is Fashion-MNIST:
https://www.kaggle.com/datasets/zalando-research/fashionmnist
It contains 28x28 grayscale images of clothing items divided into 10 classes.

## Methods
- Data loading and exploration
- Feature engineering and scaling
- PCA dimensionality reduction
- Manual KNN implementation
- Hyperparameter tuning
- 5-Fold Cross Validation
- Macro F1-score evaluation

## Final Model
The final model was trained using the best configuration found during validation.

## Evaluation
The model was evaluated on the test set using Macro F1-score.

## Files
- `fashionDetectionModel.ipynb` — main notebook with code, outputs, and explanations
