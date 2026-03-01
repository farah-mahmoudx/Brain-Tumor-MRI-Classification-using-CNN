# Brain-Tumor-MRI-Classification-using-CNN
## Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify brain MRI scans into tumor categories.

The model is trained on MRI images resized to 128x128 and normalized to improve convergence.

---

## Dataset

- Dataset: /kaggle/input/brain-tumor-mri-scans
- Structure: Each class stored in a separate folder
- Input size: 128x128 RGB images
- Preprocessing:
  - Image resizing
  - Normalization (pixel values scaled to [0,1])
