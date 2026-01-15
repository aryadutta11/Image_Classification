# Image_Classification

##  Project Overview
This project builds an end-to-end image classification system using the Intel Image Classification dataset. 
A convolutional neural network with transfer learning (ResNet50) is trained to classify natural scene images into six categories.

##  Dataset
- Source: Kaggle – Intel Image Classification
- Classes: buildings, forest, glacier, mountain, sea, street
- Total images: ~25,000

##  Methodology
- Data preprocessing and augmentation
- Baseline CNN model
- Transfer learning with ResNet50
- Model evaluation using accuracy, precision, recall, F1-score
- Explainability using Grad-CAM

##  Results
- Transfer learning significantly outperformed the baseline CNN
- Grad-CAM visualizations show the model focuses on meaningful semantic regions

##  Explainability (Grad-CAM)
The model primarily attends to structural and semantic features relevant to each class, 
demonstrating interpretable and trustworthy predictions.

##  Tech Stack
- Python
- PyTorch
- OpenCV
- Grad-CAM
- Google Colab
