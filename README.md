# Deep Learning Assignments

This repository contains four assignments implemented as Jupyter notebooks. Each assignment focuses on a different core concept in deep learning using PyTorch.

---

## Assignment 1: Deeper Regression, Smarter Features
**Notebook:** C1M1_Assigment.ipynb  

This assignment focuses on multi-feature regression using neural networks. It includes loading data from a CSV file, normalizing inputs, engineering a new feature, building a multi-layer neural network, training the model, and predicting delivery time for unseen data.

---

## Assignment 2: EMNIST Letter Detective
**Notebook:** C1M2_Assigment.ipynb  

This assignment applies image classification techniques to the EMNIST Letters dataset. It covers data loading and preprocessing, building and training a neural network to classify handwritten letters, evaluating model performance, and decoding a handwritten message using the trained model.

---

## Assignment 3: Overcoming Overfitting – Building a Robust CNN
**Notebook:** C1M4_Assigment.ipynb  

This assignment improves an overfitting convolutional neural network by enhancing the data pipeline, introducing data augmentation, refactoring the model into modular CNN blocks, and applying regularization techniques such as batch normalization, dropout, and weight decay.

---

## Assignment 4: Plant Type Classification
**Notebook:** plants_type.ipynb  

This assignment focuses on classifying plant types from image data. It includes preprocessing images, building a convolutional neural network, training the model, and evaluating its performance on unseen plant images.

## Project: Saudi License Plate Detection and Recognition
**Notebook:** car_plates.ipynb
### Overview
- YOLO model trained for **license plate detection localization (cropping)**
- YOLO model trained for **plate character recognition** with **27 classes** (numbers + letters)
- **PaddleOCR** used to to try character recognition
- Final pipeline performs **end-to-end inference on a single image**
- Outputs results in **Arabic and Latin letters**

### How to Use
1. Update the paths to:
   - Plate detection YOLO model
   - Character recognition YOLO model
   - Input image
2. Run the notebook pipeline cell to get inference results


   note: the YOLO character recognition may have weak results due to the bad labeling on the training dataset.  
