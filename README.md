# Brain Tumor MRI Classification System

Brain Tumor MRI Classification System that uses MRI scan images from separate training and testing folders to classify scans into four categories: glioma tumor, meningioma tumor, pituitary tumor, and no tumor. The project applies image preprocessing, transfer learning with EfficientNetB0, and performance evaluation techniques to build an intelligent model capable of predicting tumor type from uploaded MRI images.

## Overview

This project was developed to assist in automated brain tumor classification using MRI scan images. It applies transfer learning on medical imaging data to identify tumor type from input scans and demonstrates the use of deep learning in healthcare-oriented computer vision.

## Classes

The model classifies MRI scans into the following four classes:

- glioma_tumor
- meningioma_tumor
- pituitary_tumor
- no_tumor

## Dataset Structure

```text
dataset/
├── Training/
│   ├── glioma_tumor/
│   ├── no_tumor/
│   ├── meningioma_tumor/
│   └── pituitary_tumor/
└── Testing/
    ├── glioma_tumor/
    ├── no_tumor/
    ├── meningioma_tumor/
    └── pituitary_tumor/
