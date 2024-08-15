# A Depth Analysis on Lymphatic Node Metastatic, Non-metastatic, and Cancerous Tissue Classification using Novel Deep Neural Architecture

## Overview

This repository contains the implementation of the **SEResNet50SA** model, a novel deep neural architecture optimized for both binary and multiclass classification of medical images. The model integrates squeeze-and-excitation (SE) mechanisms with ResNet50 and Self-Attention to achieve state-of-the-art performance on several medical image datasets.

## Key Features

- **Model Architecture**: SEResNet50SA incorporates the SE mechanism alongside the ResNet50 backbone and Self-Attention layers, improving both feature extraction and classification accuracy.
- **Binary Classification**: Achieved exceptional accuracy on the PCam and BreakHIS datasets for distinguishing metastatic from non-metastatic lymph node tissue.
  - **PCam dataset**: 99.88% accuracy
  - **BreakHIS dataset**: 99.29% accuracy (across all magnification levels)
- **Multi-class Classification**: Demonstrated superior performance in categorizing cancerous tissues into distinct classes across multiple datasets.
  - **BreakHIS dataset**: 96% accuracy across 8 classes and multiple magnifications (40x, 100x, 200x, 400x)
  - **BACH dataset**: 100% accuracy across 4 distinct classes
- **Versatility Across Datasets**: Validated on three diverse medical datasets: PCam (lymph node sections), BreakHIS (breast cancer histopathology images), and BACH (breast tissue histology).
  
## Datasets

The model was trained and tested on the following datasets:
- **PCam**: PatchCamelyon dataset, focused on lymph node section images for binary classification of metastatic vs non-metastatic tissues.
- **BreakHIS**: Breast Cancer Histopathological Image Classification dataset, used for both binary and multiclass classification tasks across various magnifications (40x, 100x, 200x, 400x).
- **BACH**: Breast Cancer Histology Challenge dataset, used for multiclass classification of breast tissue histology.

## Model Performance

- **Binary Classification**:
  - PCam: **99.88%**
  - BreakHIS: **99.29%** (all magnification levels)
  
- **Multi-class Classification**:
  - BreakHIS: **96%** (8 classes)
  - BACH: **100%** (4 classes)

## Installation

To use this repository, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository

