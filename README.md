# Handwritten Character Recognition using CNN

A simple handwritten character recognition model built with PyTorch.

The model classifies 62 classes:
- `0-9`
- `A-Z`
- `a-z`

Input images are grayscale `64x64` tensors.

## Features

- Custom CNN architecture
- 5-Fold Cross Validation
- Batch Normalization + Dropout
- Model checkpoint saving
- Training/Validation accuracy tracking
- PyTorch implementation

## Dataset

- 62 classes
- 44 samples per class
- Images stored as tensors using `torch.save()`

## Model

Architecture includes:
- Convolution layers
- ReLU activation
- MaxPooling
- BatchNorm
- Fully Connected layers

Loss Function:
- CrossEntropyLoss

Optimizer:
- Adam

## Final Results

```text
Test Accuracy : 85.45%
Test Loss     : 0.4881
