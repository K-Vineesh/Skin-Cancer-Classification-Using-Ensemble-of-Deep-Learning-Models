# Skin Cancer Classification using Ensemble of Convolutional Neural Networks

This repository contains the implementation of our published research paper:

📄 **Title:** *Skin Cancer Classification using Multiple Convolutional Neural Networks*  
📚 **Journal:** Journal of Soft Computing Paradigm (Volume 5, Issue 4, Dec 2023)  
🔗 **DOI:** [10.36548/jscp.2023.4.001](https://doi.org/10.36548/jscp.2023.4.001)

## 📌 Overview

Skin cancer is among the most common cancers worldwide. Early and accurate classification of skin lesions is crucial for timely treatment. This project explores the effectiveness of **ensemble deep learning** techniques to classify various types of skin cancer using dermoscopic images.

We implement and compare the performance of the following CNN architectures:

- VGG-16
- ResNet-50
- DenseNet-201
- EfficientNetB0
- Custom Sequential CNN

The ensemble strategy aggregates the predictions from these models, improving classification performance beyond any single model.

---

## 🧠 Core Contributions

- Development and evaluation of five distinct CNN models for skin cancer classification.
- Use of transfer learning for pretrained models (e.g., VGG-16, ResNet-50).
- Implementation of an **ensemble voting mechanism** that combines the predictions from all models.
- Achieved higher accuracy and generalization compared to individual networks.

---

## 📁 Dataset

We used the **HAM10000** dataset which consists of over 10,000 dermoscopic images of pigmented skin lesions categorized into 7 classes:

- Actinic keratoses (akiec)
- Basal cell carcinoma (bcc)
- Benign keratosis-like lesions (bkl)
- Dermatofibroma (df)
- Melanoma (mel)
- Melanocytic nevi (nv)
- Vascular lesions (vasc)

📦 [Download HAM10000 dataset](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/K-Vineesh/Skin-Cancer-Classification-Using-Ensemble-of-Deep-Learning-Models.git
cd skin-cancer-ensemble-cnn
