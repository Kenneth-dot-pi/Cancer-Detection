# Skin -Cancer-Detection
AI Cancer Detection
Skin Cancer Detection Using AI

Introduction

This project focuses on AI-based skin cancer detection using image classification techniques. The system aims to assist in early diagnosis by analyzing skin lesion images and predicting whether they are cancerous or non-cancerous. The approach integrates machine learning models such as ANN, CNN, KNN, and GAN for accurate classification.

Features

Automated Skin Cancer Detection using deep learning.

Image Processing: Hair removal, noise reduction, contrast enhancement, and resizing.

Segmentation Techniques: Edge-based, region-based, active contours, histogram-based thresholds.

Feature Extraction: Asymmetry, diameter, compactness, borders, blue-white veil.

Machine Learning Models: ANN, CNN, KNN, and GAN.

Performance Metrics: Accuracy, specificity, sensitivity.

Prediction Output: Classifies lesions as cancerous or non-cancerous.

Dataset

The dataset consists of dermoscopic images collected from publicly available sources such as ISIC, PH2, and HAM10000. The images are preprocessed before training.

Installation & Requirements

To set up the project locally, install the necessary dependencies:

pip install tensorflow keras numpy pandas opencv-python matplotlib scikit-learn

Usage

Data Collection & Preprocessing

Collect skin lesion images from datasets.

Apply preprocessing steps: noise removal, contrast enhancement, and resizing.

Model Training

Train models using the processed dataset.

Validate models using testing data.

Prediction

Upload a new image.

The system classifies it as non-cancerous or cancerous.

Evaluation Metrics

The model performance is evaluated based on:

Accuracy: Measures correct predictions.

Specificity: Identifies non-cancerous cases correctly.

Sensitivity: Detects cancerous lesions accurately.

Future Improvements

Mobile application integration.

Support for different skin tones and lighting conditions.

Expanding dataset diversity.

Improved explainability of AI predictions.

Contribution

Feel free to contribute by improving model performance, adding features, or enhancing documentation. Fork the repository and submit a pull request!

License

This project is open-source and available under the MIT License.

