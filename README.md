# brain-tumor-segmentation
"Brain Tumor Segmentation from MRI Scans using Deep Learning"

This project focuses on developing an **automated deep learning-based system** to perform **brain tumor segmentation** from **MRI scans**.  
The system assists doctors by accurately identifying tumor regions, which can significantly improve diagnosis and treatment planning.  
This project demonstrates skills in **medical image analysis, computer vision, and deep learning**.

# Project Overview

Brain tumor segmentation is a crucial process in medical imaging that helps radiologists locate and analyze tumor-affected areas in MRI scans.  
This project leverages **Convolutional Neural Networks (CNNs)** and the **U-Net architecture** to perform **pixel-level tumor segmentation** on MRI data.

The system processes multi-modal MRI scans (T1, T1c, T2, and FLAIR), detects tumor regions, and visualizes the segmented areas.  
It provides both quantitative metrics and visual outputs for evaluation.

# Deep Learning Architecture

The model is based on the **U-Net** architecture — a fully convolutional neural network designed for biomedical image segmentation.

**U-Net Highlights:**
- Encoder–Decoder structure
- Skip connections for fine feature recovery
- Efficient training with limited data
- Suitable for medical image segmentation

# Evaluation Metrics

| Metric | Description |
|---------|-------------|
| **Dice Coefficient** | Measures overlap between predicted and actual segmentation. |
| **IoU (Jaccard Index)** | Evaluates intersection over union of predicted vs ground truth regions. |
| **Accuracy** | Measures correct classification of pixels. |

# Tools & Technologies

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python |
| **Frameworks** | TensorFlow / Keras or PyTorch |
| **Image Processing** | OpenCV |
| **Data Handling** | NumPy, Pandas |
| **Visualization** | Matplotlib, Seaborn |
| **Dataset** | BraTS (Brain Tumor Segmentation) Dataset |

# Dataset
Dataset Link => https://www.kaggle.com/datasets/awsaf49/brats2020-training-data

# How to Run the Project

1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/brain-tumor-segmentation.git
   cd brain-tumor-segmentation
