# Lightweight CNN for CIFAR-10 Image Classification

A custom Convolutional Neural Network built from scratch using TensorFlow/Keras, trained on the CIFAR-10 dataset achieving **84.29% test accuracy**.

## Model Architecture
- 3-block CNN with filter depths 32 → 64 → 128
- BatchNormalization + Dropout for regularization
- 128-neuron Dense classifier head with Softmax output

## Features
- Real-time data augmentation (rotation, flips, zoom, shear)
- Adam optimizer with ReduceLROnPlateau scheduling
- Full evaluation: confusion matrix, per-class precision, recall & F1

## Results
| Class | F1-Score |
|-------|----------|
| Automobile | 0.94 |
| Horse | 0.89 |
| Airplane | 0.87 |
| Cat | 0.71 |

## Tech Stack
Python · TensorFlow · Keras · NumPy · Scikit-learn · OpenCV · Matplotlib
