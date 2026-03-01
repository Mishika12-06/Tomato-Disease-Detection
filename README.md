# Tomato Leaf Disease Detection using Deep Learning
#Project Overview
This project focuses on detecting tomato leaf diseases using Deep Learning techniques. 
Initially, a custom Convolutional Neural Network (CNN) model was developed and trained. 
To improve performance and achieve better generalization, Transfer Learning using MobileNetV2 was implemented.
# Models Used
# Custom CNN Model
- Built from scratch using Conv2D, MaxPooling, Flatten, and Dense layers
- Trained on tomato leaf dataset
- Used for baseline performance comparison
# MobileNetV2 (Transfer Learning)
- Pretrained on ImageNet
- Fine-tuned on tomato leaf dataset
- Improved feature extraction and accuracy
- Faster convergence and better generalizatio
#Dataset
The dataset contains three categories:
- Healthy
- Early Blight
- Late Blight
Due to size limitations, the dataset is not uploaded directly to GitHub.
Download Dataset:
[Download Here](https://drive.google.com/file/d/1dF-mH4nz7G_sTLOTaOgqR8MgiTqTXEYt/view?usp=sharing)
# Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- OpenCV
#Project Workflow
1. Data Preprocessing
2. Image Resizing and Normalization
3. Model Building (CNN)
4. Model Improvement using MobileNetV2
5. Training and Validation
6. Model Evaluation
7. Model Saved as `.h5` file
# Model File
The trained model is saved in `.h5` format and can be used for inference.

# Key Highlights
- Implemented both custom CNN and Transfer Learning approach
- Compared performance between baseline and pretrained model
- Applied deep learning concepts for real-world agricultural problem
