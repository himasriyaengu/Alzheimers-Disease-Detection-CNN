# Alzheimer's Disease Detection using Convolutional Neural Networks

## Overview

This project presents a deep learning-based approach for Alzheimer's Disease detection using MRI brain scan images. The system focuses on hippocampus-based MRI slice selection and evaluates Convolutional Neural Network architectures for medical image classification.

Alzheimer's Disease affects memory and cognitive function, and early diagnosis is important for improving patient care. MRI-based analysis is useful because structural changes in the hippocampus are strongly associated with Alzheimer's progression.

---

## Key Features

* MRI brain image preprocessing
* Hippocampus-focused slice selection
* Multi-view MRI analysis: Axial, Coronal, and Sagittal
* CNN-based Alzheimer's Disease classification
* Model comparison using ResNet50, LeNet, and Extended LeNet
* Test image prediction workflow
* Medical imaging and healthcare AI application

---

## Dataset

The project uses MRI brain images inspired by the Alzheimer's Disease Neuroimaging Initiative (ADNI) dataset.

The dataset is not included in this repository due to size and licensing limitations. Dataset reference information is provided in:

```text
DatasetLInk.txt
```

The implementation processes MRI images across three anatomical views:

* Axial
* Coronal
* Sagittal

---

## Methodology

The project workflow includes:

1. Upload MRI dataset
2. Preprocess MRI images
3. Normalize and resize images
4. Split data into training and testing sets
5. Train CNN-based models
6. Compare model performance
7. Upload test MRI image
8. Predict Alzheimer's-related classification output

---

## Models Used

* ResNet50
* LeNet
* Extended LeNet

The project evaluates these models to identify effective deep learning architectures for MRI-based Alzheimer's Disease detection.

---

## Repository Structure

```text
Alzheimers-Disease-Detection-CNN/
│
├── AlzheimerDetection.ipynb
├── DatasetLInk.txt
├── requirements.txt
├── README.md
│
└── testImages/
```

---

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Applications

* Medical Image Analysis
* Alzheimer's Disease Detection
* Computer-Aided Diagnosis
* Healthcare Artificial Intelligence
* MRI-Based Classification
* Deep Learning Research

---

## Results

The project demonstrates that selecting informative hippocampus-related MRI slices can improve classification performance compared to using full MRI scan inputs. The system compares CNN-based architectures and supports prediction on unseen MRI test images.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/himasriyaengu/Alzheimers-Disease-Detection-CNN.git
```

2. Navigate to the project folder:

```bash
cd Alzheimers-Disease-Detection-CNN
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Open the notebook:

```bash
jupyter notebook AlzheimerDetection.ipynb
```

---

## Author

**Himasriya Engu**
M.S. Computer Science
University of Central Florida

**Research Interests**

* Machine Learning
* Deep Learning
* Computer Vision
* Medical AI
* Healthcare Analytics

---

⭐ If you found this project helpful, consider starring the repository.
