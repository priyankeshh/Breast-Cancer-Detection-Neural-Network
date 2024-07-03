# Breast Cancer Detection using Neural Networks

## Overview
This project implements a neural network model for detecting breast cancer based on Wisconsin Diagnostic Breast Cancer (WDBC) dataset. The neural network is trained to classify tumors as benign or malignant based on various features extracted from diagnostic images.

## Dataset
The dataset used for this project is the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, which contains features computed from digitized images of fine needle aspirate (FNA) of breast masses.

## Methodology
- **Preprocessing:** Data preprocessing involved standardization of feature values and encoding the target labels.
  
- **Model Architecture:** The neural network model consists of multiple layers including input layer, hidden layers with ReLU activation, and an output layer with sigmoid activation for binary classification.

- **Training:** The model was trained using backpropagation with binary cross-entropy loss function and Adam optimizer. 

- **Evaluation Metrics:**
  - Accuracy: 0.9474
  - Precision: 0.9475
  - Recall: 0.9474
  - F1 Score: 0.9471

## Results
The trained neural network achieved promising results with an overall accuracy of 94.74% on the test set, demonstrating its effectiveness in classifying breast tumors.

## Usage
- **Dependencies:** Ensure Python 3.x and necessary libraries such as NumPy, Pandas, and TensorFlow are installed.


## Credits
This project was developed by [@Priyankesh](https://github.com/priyankeshh) as part of [mention any course or program if applicable].
