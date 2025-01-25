# LiteCNNRice
# Rice Leaf Disease Classification using Resource-Efficient Deep Learning Models via Response-Based Knowledge Distillation

## Overview

This repository contains the implementation of a deep learning model for rice leaf disease classification, utilizing resource-efficient techniques via Response-Based Knowledge Distillation (KD). The aim of this project is to enhance the performance of a lightweight model by transferring knowledge from a larger, pre-trained teacher model to a smaller, more efficient student model, all while maintaining high classification accuracy.

The approach significantly reduces computational overhead, making the solution more viable for deployment in resource-constrained environments. This repository includes the following materials:

- The trained model files (`.h5`, `.json`)
- An analysis notebook (`Model_Analysis.ipynb`)
- The dataset used for training, validation, and testing

This work was presented in the paper titled "**Rice Leaf Disease Classification using Resource-Efficient Deep Learning Models via Response-Based Knowledge Distillation**."

## Contents

1. **Model Files**
   - `model.h5`: The trained student model after distillation.
   - `model.json`: The model architecture in JSON format.
   
2. **Model Analysis**
   - `Model_Analysis.ipynb`: Jupyter notebook detailing the analysis of the model's performance, including evaluation metrics, confusion matrix, and insights gained from the distillation process.

3. **Dataset**
   - `train/`: Folder containing the training dataset.
   - `val/`: Folder containing the validation dataset.
   - `test/`: Folder containing the testing dataset.

## Key Features

- **Resource Efficiency**: By leveraging Response-Based Knowledge Distillation, this project demonstrates how a complex teacher model can impart knowledge to a smaller student model, resulting in significant resource savings while maintaining high accuracy.
- **Classification Task**: The model is trained to classify rice leaf diseases into various categories based on image inputs, which can aid in early diagnosis and agricultural decision-making.

## Getting Started

### Prerequisites

To run the code and evaluate the model, you need the following dependencies:

- Python 3.x
- TensorFlow/Keras (for model loading and evaluation)
- NumPy, Pandas (for data manipulation)
- Matplotlib, Seaborn (for visualization)
- OpenCV (for image processing)
  
You can install the required dependencies using the following:

```bash
pip install -r requirements.txt

