# MNIST Classification using PyTorch

## Overview
This project implements an MNIST digit classifier using **PyTorch**. The model is trained on the **MNIST dataset**, and an additional feature is included to **display the probability of each digit prediction** using matplot lib as a graph for selected sample. Additionally, incorrect predictions are **segregated** for analysis.

## Features
- **Trains a deep learning model** on the MNIST dataset.
- **Predicts and displays probability scores in a bar graph** for selected digit.
- **Identifies and segregates incorrect predictions** for further analysis.
- Uses **PyTorch** for training and evaluation.

## Installation
To run this project, ensure you have Python 3 and install the dependencies(Or you can use **Google Colab** as I did):
```bash
pip install torch torchvision numpy scikit-learn matplotlib
