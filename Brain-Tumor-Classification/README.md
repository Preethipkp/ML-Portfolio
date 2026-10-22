# Brain Tumor Classification Using CNN

## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify brain MRI images into four categories: Glioma Tumor, Meningioma Tumor, No Tumor, and Pituitary Tumor.

## Technologies Used
- Python
- Keras
- NumPy
- scikit-image
- Matplotlib
- Scikit-learn

## Dataset
The images are organized into four categories:
- Glioma Tumor
- Meningioma Tumor
- No Tumor
- Pituitary Tumor

Images are resized to 150 × 150 pixels with one channel.

## CNN Architecture
1. Conv2D layer with 32 filters and ReLU activation
2. MaxPool2D layer
3. Flatten layer
4. Dense layer with 100 neurons and ReLU activation
5. Output Dense layer with 4 neurons and Softmax activation

## Model Training
- Optimizer: Adam
- Loss function: Sparse categorical cross-entropy
- Epochs: 10
- Batch size: 12

## Evaluation and Prediction
The model is evaluated on testing images. A classification report is used to examine its performance. The trained model also predicts the category of an individual MRI image, which is displayed using Matplotlib.

## Saved Model
`brain_tumor_cnnmodel.keras`

## Disclaimer
This project is for educational purposes only. It is not a clinically validated diagnostic system and should not be used to make medical decisions.
