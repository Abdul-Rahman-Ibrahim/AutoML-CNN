# CNN Implementation in PyTorch

This repository contains a custom CNN (Convolutional Neural Network) class built in PyTorch, allowing flexible layer configuration.

## Features
- Configurable convolutional layers with custom kernel sizes, paddings, and strides.
- MaxPooling with configurable pool sizes.
- Fully connected layers for classification or regression tasks.
- Flexible input shape and channels.
- Training with optional test evaluation.

## Class Initialization

```python
CNN(
    input_shape: Tuple[int, int],
    conv_sizes: List[Tuple[int, int, int, int]],
    pool_sizes: List[int],
    fc_sizes: List[int],
    in_channel: int = 1
)

```
# USAGE EXAMPLE
[Test JupyterNotebook](./test.ipynb)
