# Tuberculosis Detection Using YOLOv8

![TB Detection](https://img.shields.io/badge/Status-Active-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![YOLOv8](https://img.shields.io/badge/Model-YOLOv8-orange)

---

## 📋 Project Overview

This repository contains an implementation of **Tuberculosis (TB) detection** from chest X-ray images using the **YOLOv8** object detection model. The goal is to automatically identify and localize tuberculosis-infected regions in X-rays to assist radiologists and healthcare professionals.

---

## 🩻 Dataset

- The dataset consists of chest X-ray images labeled for **Tuberculosis detection**.
- It includes **bounding box annotations** marking TB-infected regions.
- The dataset is split into:
  - **Train Images**: 1877
  - **Train Labels**: 1877
  - **Validation Images**: 260
  - **Validation Labels**: 260
  - **Test Images**: 150
  - **Test Labels**: 150

---

## 🚀 Features

- Fine-tuning YOLOv8 model on a TB X-ray dataset.
- Custom data augmentation tailored for medical images.
- Visualization scripts to display images with predicted bounding boxes.
- Evaluation metrics for model performance.
- Easy-to-use training and inference scripts.

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/codewith-rawad/YOLOv8-TB-Detection.git
   cd YOLOv8-TB-Detection
