# 🧬 C-Pred: Skin Lesion Classification

> An end-to-end deep learning pipeline for the classification of skin lesions using **YOLOv8** and **PyTorch**.  
This project includes data preprocessing, model training, interpretability visualizations (Grad-CAM & heatmaps), and a final report.

---

## 📑 Table of Contents

1. [Description](#-description)  
2. [Features](#-features)  
3. [Prerequisites](#-prerequisites)  
4. [Installation](#-installation)   
5. [Configuration](#-configuration)  
6. [Project Architecture](#-project-architecture)  
 

---

## 📖 Description

C-Pred is a research-oriented project focused on **automated skin lesion classification** using deep learning techniques.  
It leverages **YOLOv8** for classification, combined with PyTorch for model training and Grad-CAM for interpretability.  

The project provides:  
- Preprocessing of medical imaging data  
- Training pipelines with YOLOv8 and EfficientNet  
- Model evaluation metrics  
- Heatmap visualizations for interpretability  
- A structured and reproducible workflow  

---

## ✨ Features

- 🔬 Data preprocessing and augmentation  
- 🤖 Training and evaluation of deep learning models  
- 📊 Grad-CAM & heatmap visualization for interpretability  
- 📄 Full documentation with PDF report  
- ⚡ Easy setup with `requirements.txt`  
- 📦 Pretrained weights available with **Git LFS**  

---

## 🛠️ Prerequisites

- **Operating System**: Linux, macOS, or Windows  
- **Python**: 3.10+  
- **Dependencies** (see `requirements.txt`):  
  - PyTorch ≥ 2.0  
  - Torchvision ≥ 0.15  
  - Ultralytics YOLOv8 ≥ 8.0  
  - Scikit-learn ≥ 1.3  
  - OpenCV (headless) ≥ 4.10  
  - Pillow ≥ 10.0  
  - Matplotlib, NumPy, Requests  

---

## ⚙️ Installation

**Clone the repository**
```bash
git clone https://github.com/AntoineBoukhelifa/-c-pred-skin-lesion-classification.git
cd -c-pred-skin-lesion-classification
```

---

## 🔧 Configuration

**Files**
- `requirements.txt` → Python dependencies  
- `models_weights/` → pretrained model weights (managed via Git LFS)  

**Optional environment variables**  
You can create a `.env` file to customize paths:
```env
```
DATASET_PATH=/path/to/data
OUTPUT_PATH=/path/to/output
---

## 🏗️ Project Architecture

cpred/
├── notebooks/                  # Jupyter notebooks
│   ├── data_processing.ipynb   # Data preprocessing and cleaning
│   ├── demo_soutenance.ipynb   # Presentation demo
│   ├── heatmap.ipynb           # Grad-CAM and heatmap visualization
│   └── models.ipynb            # Model training and evaluation
│
├── models_weights/             # Pretrained model weights (tracked with Git LFS)
│   ├── best.pt
│   └── yolov8x-cls.pt
│
├── docs/
│   └── Final_report.pdf        # Full project report
│
├── requirements.txt            # Python dependencies
└── README.md                   # Project documentation


