# Handwritten Digit Classification with MLP

This project uses a **Multilayer Perceptron (MLP)** neural network to classify handwritten digits (0-9) from the **scikit-learn Digits dataset**.

## Key Features
- **Dataset**: The model is trained on 8x8 pixel images of handwritten digits (0-9) from the scikit-learn Digits dataset.
- **MLP Classifier**: A neural network with configurable hidden layers is used to learn the mapping between image pixels and digit labels.
- **Train/Test Split**: The dataset is split into training and testing sets to evaluate model performance.
- **Visualization**: Includes visualization of:
  - Hidden layer weights.
  - Prediction probabilities for individual test samples.
  - Identification of low-confidence predictions.

## Dependencies
- `numpy`
- `matplotlib`
- `scikit-learn`

To install the dependencies, run:
```bash
pip install numpy matplotlib scikit-learn
```

## How to use
- Train the MLP classifier.
- Visualize hidden layer weights and prediction probabilities.
- Analyze model confidence on test samples.