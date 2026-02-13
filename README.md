## 📌 Project Overview

This project implements image classification on the **Intel Natural Scenes Dataset** using:

- A baseline Convolutional Neural Network (CNN)
- Transfer Learning with ResNet50 (pretrained on ImageNet)

The goal is to classify images into six scene categories and compare performance between a custom CNN and a pretrained deep network.

---

## 📂 Dataset

**Dataset Used:** Intel Natural Scenes Dataset  
Classes:
- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

Total Images: ~25,000  
Training Images: ~14,000  
Testing Images: ~3,000  

Images were resized to **150x150 pixels**.

Dataset downloaded using:
```python
import kagglehub
path = kagglehub.dataset_download("puneet6060/intel-image-classification")
