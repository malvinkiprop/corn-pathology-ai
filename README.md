# 🌽 Corn Pathology AI

## AI-Powered Maize Disease Detection System

Corn Pathology AI is a computer vision and deep learning project designed to detect and classify maize leaf diseases from images.

The project follows an end-to-end machine learning workflow, beginning with image dataset validation and exploratory analysis, followed by preprocessing, model development, evaluation, error analysis, confidence analysis, and deployment preparation.

---

## 📌 Project Overview

Maize is an important agricultural crop, and plant diseases can negatively affect crop health and productivity.

This project explores how computer vision and deep learning can be used to identify maize leaf diseases from images.

The system analyses images of maize leaves and predicts the disease class associated with the image.

The project focuses not only on model development, but also on the data science process surrounding the model, including:

- Dataset validation
- Data cleaning
- Exploratory data analysis
- Image quality analysis
- Image preprocessing
- Model training
- Model comparison
- Performance evaluation
- Error analysis
- Prediction confidence analysis
- Deployment preparation

---

# 🎯 Project Objectives

The main objectives of the project were to:

1. Validate the quality and structure of the maize leaf image dataset.
2. Identify invalid or problematic image files.
3. Analyse the distribution and characteristics of the dataset.
4. Prepare images for deep learning.
5. Develop image classification models.
6. Compare model performance using appropriate evaluation metrics.
7. Analyse model errors and areas of confusion.
8. Investigate prediction confidence.
9. Prepare the solution for deployment as an AI-powered application.

---

# 📊 Dataset

The project used a maize leaf image dataset containing:

- **4,184 verified images**
- **4 disease classes**

The dataset underwent validation and quality checks before being used for model development.

The image dataset itself is **not included in this GitHub repository** because of its size.

The repository contains the main project notebook and documentation required to understand the project.

---

# 🧹 Data Validation and Cleaning

Before model training, the image dataset was inspected and validated.

The data preparation process included:

- Checking whether image files could be opened successfully
- Validating image files
- Identifying invalid images
- Checking image dimensions
- Analysing image width and height
- Calculating aspect ratios
- Analysing image file sizes
- Checking image area
- Generating dataset quality statistics
- Checking for duplicate images using file hashes

The cleaning process was designed to identify problematic files without unnecessarily deleting the original image dataset.

---

# 🔎 Exploratory Data Analysis

Exploratory analysis was performed to understand the structure and characteristics of the image dataset.

The analysis included:

- Class distribution
- Image dimensions
- Image aspect ratios
- File sizes
- Image area
- Dataset quality
- Distribution of images across disease categories

Understanding the dataset before training helped identify potential data-quality issues and provided context for interpreting model performance.

---

# 🖼️ Image Preprocessing

Images were prepared for deep learning using TensorFlow.

The preprocessing workflow included:

- Loading image files
- Decoding images
- Converting images to three colour channels
- Resizing images
- Preserving image aspect ratio
- Padding images where necessary
- Converting image values to floating-point tensors
- Creating TensorFlow datasets
- Batching the data
- Shuffling the training data
- Prefetching batches for efficient training

The project used:

```text
Image Size: 224 × 224
Batch Size: 32
---

#MACHINE LEARNING WORKFLOW
Maize Leaf Images
        ↓
Data Validation
        ↓
Data Cleaning
        ↓
Quality Analysis
        ↓
Exploratory Data Analysis
        ↓
Image Preprocessing
        ↓
Dataset Preparation
        ↓
Model Training
        ↓
Model Comparison
        ↓
Model Evaluation
        ↓
Error Analysis
        ↓
Confidence Analysis
        ↓
Deployment Preparation