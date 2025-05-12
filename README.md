# Computer Vision Projects in Python

This repository contains two distinct yet educational computer vision projects implemented using Python and Jupyter Notebooks: one for **Automatic Number Plate Detection** and another for **Brain Tumor Classification** using deep learning. Both projects demonstrate practical applications of image processing and AI in real-world scenarios.

---

## 🚗 Number Plate Detection

The Number Plate Detection project presents a classic computer vision pipeline to detect and localize vehicle license plates from static images using OpenCV. The system preprocesses images through grayscale conversion, noise removal, edge detection, and contour analysis to isolate regions that match license plate characteristics. This approach is efficient, does not require heavy datasets, and can be extended to real-time video streams and integrated with OCR for full ANPR (Automatic Number Plate Recognition) systems. Ideal use cases include smart parking, traffic monitoring, and vehicle access control systems.

### Key Features:
- Image preprocessing (grayscale, blurring, edge detection)
- Contour-based license plate detection
- Simple, real-time capable architecture
- Easy to modify and integrate with OCR

---

## 🧠 Brain Tumor Classification

The Brain Tumor Classifier is a deep learning-based project designed to classify MRI images as either having a tumor or not. It uses a convolutional neural network (CNN) built with TensorFlow/Keras to learn and identify patterns from medical imaging data. The notebook includes data preprocessing, model training, evaluation metrics, and visualizations. This project serves as a foundation for building AI-driven diagnostic tools in medical imaging and can be extended with transfer learning, segmentation, or multi-class classification.

### Key Features:
- CNN-based classification of MRI brain scans
- Image normalization and augmentation
- Training with accuracy and loss visualization
- Evaluation with metrics like precision, recall, and confusion matrix

---

## 📦 Requirements

To run these projects, ensure you have the following Python packages installed:

- `numpy`
- `opencv-python`
- `matplotlib`
- `tensorflow`
- `keras`
- `scikit-learn`
- `seaborn` (optional for visualization)
