# Tumor Detection Using Deep Learning

## Overview  
This project implements a **Convolutional Neural Network (CNN)** to classify **breast ultrasound images** into three categories:  
- **Benign tumor**  
- **Malignant tumor**  
- **No abnormality**  

The goal is to explore deep learning for medical image classification and provide a reproducible pipeline for data preprocessing, training, evaluation, and visualization.

---

## Dataset
This project uses a clean set of 2D breast ultrasound images.
A great example is the Breast Ultrasound Images Dataset on Kaggle.

## Model Architecture
The CNN is built using PyTorch and includes:
- 3 × Convolution → BatchNorm → ReLU → MaxPool blocks
- Flatten layer → Fully Connected layers with Dropout
- Cross-Entropy Loss for multi-class classification

## Results
- **Accuracy:** ~88% on the test set
- **Loss Function:** Cross-Entropy Loss
- **Visualization:** Training & validation curves tracked in TensorBoard

## Project Applications
This project demonstrates how CNNs can be applied to medical imaging tasks and may be extended to:
- Multi-class tumor classification
- Transfer learning with pretrained models
- Explainability techniques (Grad-CAM, saliency maps)

## Future Improvements
- Implement data balancing techniques (e.g., SMOTE, class-weighted loss)
- Experiment with deeper architectures (ResNet, DenseNet, Vision Transformers)
- Deploy model as a simple web app for clinicians to test predictions
