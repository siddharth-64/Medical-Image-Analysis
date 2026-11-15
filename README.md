# Medical Image Analysis

## Overview

Medical image analysis plays an important role in modern healthcare by helping identify patterns, extract meaningful information, and support clinical decision-making. This project focuses on applying deep learning techniques to medical image analysis to improve the accuracy and efficiency of image-based predictions.

The objective is to develop a deep learning pipeline that can process medical images, learn relevant visual features, and generate predictions to assist in medical image assessment.

![Application Preview](images/app_image.png)

## Model Development and Results

- Developed a unified pipeline for dataset preprocessing, model training, and evaluation.
- Implemented **Transfer Learning** using the **InceptionV3** architecture to leverage pretrained feature representations and improve model performance.
- Fine-tuned the pretrained model to adapt it to the characteristics of the medical imaging datasets.
- Applied **Train-Time Data Augmentation** to increase dataset diversity, improve generalization, and reduce overfitting.
- Used **Test-Time Augmentation (TTA)** to improve prediction robustness across variations in image orientation, illumination, and other imaging conditions.
- Evaluated model performance using multiple evaluation metrics. Detailed results are available in the `Test evaluation metrics` directory.

## Technologies and Tools

- **Programming Language:** Python 3.10.1
- **Deep Learning:** TensorFlow, Keras
- **Web Framework:** Streamlit 1.13.0
- **Image Processing:** OpenCV, PIL
- **Data Processing:** NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn

## Project Structure

```text
Medical-Imaging-Analysis/
│
├── images/
│   └── app_image.png
│
├── Test evaluation metrics/
│
├── README.md
└── ...
```

## Application

The project includes a Streamlit-based interface that allows users to interact with the trained model and perform medical image analysis through a simple interface.
