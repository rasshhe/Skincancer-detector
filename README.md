# Skin Cancer Detection  
Deep Learning-Based Binary Classification Model

## Overview  
A deep learning-powered web application built with Keras, Streamlit, and Ngrok to detect Skin Cancer from skin lesion images. This tool enables real-time prediction of whether an uploaded image shows signs of cancer or not.

## Features  
Model Building  
- Custom CNN architecture using Keras Sequential API  
- Input image shape: 224x224x3  
- Layers: Conv2D, MaxPooling, Dropout, Dense with sigmoid output  
- Binary classification: Cancer / Non-Cancer

Image Handling  
- Dataset directory structure with `train`, `val`, and `test` folders  
- Real-time image augmentation using `ImageDataGenerator`  
- Automated preprocessing and batch loading

Training & Evaluation  
- Epoch-based training with validation tracking  
- Loss: Binary Crossentropy  
- Optimizer: Adam  
- Evaluation on test data to measure performance

Prediction  
- Upload a single image for prediction  
- Model outputs probability and class label (Cancer or Non-Cancer)

## Technical Stack  
Language: Python  
Libraries: TensorFlow, Keras, NumPy, Matplotlib  
Environment: Google Colab Compatible  
Model File: Trained `.h5` model (optional for deployment)

## Project Structure  
Skin_Cancer_Detection.ipynb — Full model development and training notebook  
README.md — Project overview and usage instructions  
requirements.txt — Dependencies used in the notebook and app  
skin_cancer_detection_model.h5 — (Optional) Trained model file for reuse  

## How to Run  
1. Open the notebook in Google Colab or Jupyter  
2. Ensure the dataset is structured in `train/`, `val/`, and `test/` directories  
3. Run all cells to train and evaluate the model  
4. Use the final section to predict new images

## Documentation  
📄 [Download Jupyter Notebook File](Skin_Cancer_Detection.ipynb)

Includes:

- Model architecture details  
- Dataset loading and augmentation  
- Code for training and prediction  
- Visualization of accuracy and loss  
- Sample output and classification logic

## Author  
Rashi Raj  
B.Tech Computer Science (AIML)  
University of Petroleum and Energy Studies  
[GitHub Profile](https://github.com/rasshhe)
