# 🧠 Early Brain Tumor Detection in MRI Images using Hybrid Deep Learning

This project aims to develop a hybrid deep learning model to classify brain MRI scans into four categories: **Glioma**, **Meningioma**, **Pituitary Tumor**, and **No Tumor**. By combining the strengths of InceptionV3 and Xception architectures, this system enables **early and accurate tumor detection**.

## 🚀 Project Highlights

- ⚙️ **Hybrid Model**: Combines InceptionV3 and Xception CNN architectures.
- 🎯 **Accuracy**: Achieved up to **99% test accuracy** on real-world datasets.
- 🧩 **Feature Fusion**: Uses Feature Pyramid Network (FPN) and Multi-Scale Feature Extraction for robust analysis.
- 🧠 **Attention Mechanisms**: Integrates dual attention (spatial + channel) to focus on key regions.
- 🔍 **Dilated Convolutions**: Captures broader contextual features without reducing resolution.
- 🖼️ **Dataset**: Used over **7,000 MRI images** from Figshare, SARTAJ, and Br35H datasets.

## 📁 Dataset

The dataset includes T1-weighted contrast-enhanced MRI images classified into 4 classes:
- Glioma
- Meningioma
- Pituitary
- No Tumor

> Total Images: 7,023  
> Source: [Figshare](https://figshare.com), [SARTAJ dataset](#), [Br35H](#)

## 🧠 Model Architecture

- Pretrained **InceptionV3** and **Xception** for feature extraction.
- Aligned feature maps using **bilinear interpolation**.
- **FPN** + **Multi-Scale Feature Extraction** for hierarchical learning.
- **Dilated convolutions** to expand the receptive field.
- **Dual Attention** to refine spatial and channel-wise relevance.
- Final classification through **Dense Softmax Layer**.

## 🛠️ Requirements

```bash
tensorflow==2.x
keras
numpy
matplotlib
opencv-python
scikit-learn





