# Project 3 - EEL4930: ANN (README.md)

## Flower Classification and Lung X-Ray Segmentation with TensorFlow

This project implements neural networks for flower classification and lung segmentation using TensorFlow.

### Datasets

- **Flower Species**: 1678 RGB images across 10 classes
- **Lungs X-Rays**: The dataset contains 704 X-rays and corresponding lung segmentation masks. Each image is grayscale and of shape 512×512.

### Code

- `training2.ipynb`: Train the flower classifier and lung segmentation networks. Includes data loading, model definition, hyperparameter tuning, and evaluation.
- `testing.ipynb`: Evaluate the trained model on the test sets.

### Instructions

1. Install TensorFlow and required libraries.
2. Open `training.ipynb` in Jupyter Notebook and run cells sequentially.
3. After training, open `test.ipynb` to evaluate the model.

### More Files
Some more files are also included:
- report.pdf
- model_cnn.keras
- model_mlp.keras
