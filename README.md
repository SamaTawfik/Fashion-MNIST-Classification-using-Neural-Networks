# Fashion-MNIST-Classification-using-Neural-Networks
This project implements and compares two neural network models for image classification using the Fashion-MNIST dataset.
The comparison is based on: - Activation functions - Number of neurons - Learning rate

## Dataset

Dataset: Fashion-MNIST

Dataset Link:
https://github.com/zalandoresearch/fashion-mnist

The dataset contains:
- 60,000 training images
- 10,000 testing images
- 10 classes

- ## Preprocessing

The following preprocessing steps were applied:
- Reshaping images from 28×28 to 784 features
- Normalization
- Train / Validation / Test split
- Data augmentation using Gaussian noise
- Conversion to PyTorch tensors

## Models

### Model 1
- Activation Function: ReLU
- Architecture: 784 → 256 → 128 → 10
- Learning Rate: 0.001

### Model 2
- Activation Function: Tanh
- Architecture: 784 → 64 → 32 → 10
- Learning Rate: 0.01

## Results

| Model | Activation Function | Accuracy |
|------|------|------|
| Model 1 | ReLU | 89.79% |
| Model 2 | Tanh | 89.81% |
## Visualizations

The project includes:
- Training loss graphs
- Validation loss graphs
- Accuracy comparison graphs

- ## Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- scikit-learn
