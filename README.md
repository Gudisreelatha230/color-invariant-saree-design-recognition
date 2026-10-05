# Color-Invariant Saree Design Recognition

A PyTorch-based computer vision project for recognizing Indian saree design patterns while exploring robustness to color variations.

## Project Overview

This project implements a saree design recognition system using deep learning.

The experiment compares:

- A ResNet-18 baseline model
- A color-invariant training configuration using image augmentation

The goal is to reduce the model's dependence on image color and improve robustness to changes in illumination and color appearance.

## Saree Design Categories

The model recognizes four design categories:

- Banarasi
- Bandhani
- Ikat
- Pichwai

## Approach

The project uses:

- Python
- PyTorch
- ResNet-18
- Image augmentation
- GPU-based training
- Model evaluation

Color-related augmentations include:

- Brightness variation
- Contrast variation
- Saturation variation
- Hue variation
- Grayscale augmentation

## Results

| Model | Test Accuracy |
|---|---:|
| ResNet-18 Baseline | 93.33% |
| Color-Invariant Training | 91.67% |

Although the color-invariant configuration produced a slightly lower test accuracy in this experiment, the augmentation strategy is intended to reduce reliance on color and improve robustness to illumination and color variations.

## Dataset

Dataset used:

**Indian Saree Patterns**

Kaggle dataset:
https://www.kaggle.com/datasets/div456/indian-saree-patterns

The dataset is not included in this repository.

## Technologies

- Python
- PyTorch
- NumPy
- Pandas
- Computer Vision
- Deep Learning
- ResNet-18

## Kaggle Notebook

The complete executed notebook is also available on Kaggle:

https://www.kaggle.com/code/gudisreelatha/color-invariant-saree-design-recognition

## Future Improvements

Possible improvements include:

- Larger and more diverse datasets
- Controlled color-shift evaluation
- Metric-learning approaches
- Saree image retrieval and verification
- More robust color-invariant representations
