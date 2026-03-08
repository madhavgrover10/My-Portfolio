## 📂 Folder Contents

NEU-Metal-Surface-Defect-Dataset → Image dataset containing different types of metal surface defects

metal_surface_defect_classification.ipynb → Complete Jupyter Notebook including data preprocessing, CNN model development, training, evaluation, and visualization

## 📘 Project Overview

This project focuses on automatically detecting and classifying metal surface defects using deep learning techniques. Surface defects such as scratches, inclusions, patches, and pitted surfaces commonly occur during manufacturing and can significantly affect product quality.

The goal of this project is to develop a Convolutional Neural Network (CNN) capable of identifying defect types from images, enabling automated inspection systems for industrial quality control.

## ⚙️ Key Steps

**Data Understanding & Exploration**

- Loaded the NEU Metal Surface Defect dataset
- Visualized sample images from each defect class
- Identified 6 defect categories:
  - Crazing
  - Inclusion
  - Patches
  - Pitted Surface
  - Rolled-in Scale
  - Scratches

**Image Preprocessing**

- Resized images to a consistent input size
- Applied normalization using torchvision transforms
- Prepared dataset using `ImageFolder`

**Dataset Preparation**

- Built efficient training and validation pipelines using PyTorch `DataLoader`
- Batched images for GPU training

**Model Development**

- Designed a custom Convolutional Neural Network (CNN)
- Architecture includes:
  - Convolutional layers
  - Activation functions
  - Pooling layers
  - Fully connected layers

**Model Training**

- Trained the CNN model using PyTorch
- Used GPU acceleration for faster training
- Monitored training loss and accuracy across epochs

**Model Evaluation**

- Evaluated the model using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Confusion Matrix

**Visualization**

- Displayed defect image samples
- Plotted training loss curves
- Generated confusion matrix heatmap
- Visualized sample predictions

## 📊 Results

🧠 Best Model: Custom CNN

Final Training Performance:

- **Training Accuracy:** 96.9%
- **Validation Accuracy:** 96.4%

Overall Test Performance:

- **Overall Accuracy:** **96%**

### Classification Report

| Defect Type | Precision | Recall | F1-score |
|-------------|-----------|--------|---------|
| Crazing | 0.91 | 1.00 | 0.95 |
| Inclusion | 1.00 | 0.88 | 0.94 |
| Patches | 1.00 | 1.00 | 1.00 |
| Pitted Surface | 0.98 | 0.98 | 0.98 |
| Rolled-in Scale | 1.00 | 0.92 | 0.96 |
| Scratches | 0.91 | 1.00 | 0.95 |

Total Samples Evaluated: **360 images**

The model achieved strong performance across most defect classes, particularly for **patches, pitted surfaces, and rolled-in scale defects**.

## 🔍 Key Insights

- CNN models are highly effective for detecting visual defects in manufacturing materials.
- Certain defects such as **inclusion** show slightly lower recall due to visual similarity with other defect types.
- Proper image preprocessing and normalization significantly improved model convergence.
- Deep learning models can successfully learn subtle texture differences in industrial surface images.

📈 Visuals Included

- Sample defect images visualization
- Training loss curve
- Confusion matrix heatmap
- Model prediction samples

## 🧠 Business Value

Automated defect detection systems can help manufacturing industries:

- Reduce manual inspection time
- Improve defect detection accuracy
- Ensure consistent product quality
- Lower operational costs due to faulty production

Such systems can be integrated into **smart manufacturing pipelines and automated inspection systems**.

## 🧾 Skills & Tools Used

Python  
PyTorch  
Computer Vision  
Deep Learning  
Convolutional Neural Networks (CNN)  
NumPy  
Matplotlib  
Scikit-learn
