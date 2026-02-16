# 🛣 Safe-Roads
**ML-Based Road Infrastructure Monitoring Lab**

## 📌 About Us

**Safe-Roads** is a research-driven initiative focused on developing an intelligent pothole detection system using computer vision and deep learning.

Our objective is to **automate road condition monitoring** to support safer transportation infrastructure.

This organization hosts all research, dataset preparation, model development, and documentation related to the **Safe-Roads project**.

## 🎯 Mission

To design and develop a **high-accuracy pothole detection system** capable of identifying road surface damage using deep learning techniques.

## 📊 Current Project Status

### Dataset Overview

**Total Images: 6,738**

| Category | Number of Images |
|----------|------------------|
| Asphalt Road | 2,000 |
| Pothole | 4,738 |

### 📂 Original Image Formats

- **HEIC** – High Efficiency Image Container
- **PNG** – Portable Network Graphics
- **JPG/JPEG** – Joint Photographic Experts Group

All images were standardized to **JPG format** for machine learning compatibility.

### 🔄 Preprocessing Steps

✔ Format conversion (HEIC/PNG => JPG)  
✔ Removal of corrupted images  
✔ Resizing to 224 × 224 pixels  
✔ Data augmentation using horizontal flipping  

### 🤖 Model Performance

- **Input size:** 224 × 224
- **Classes:** Road, Pothole
- **Road type:** Asphalt
- **Validation Accuracy:** 98%

**Current Limitation:**  
Model is trained only on asphalt road surfaces.

## 📁 Organization Repositories

| Repository | Purpose |
|------------|---------|
| `safe-roads-pothole-detection` | Core model development |
| `safe-roads-research-docs` | Research papers & reports |

## 🧠 Technologies Used

- Python
- Deep Learning (CNN-based model)
- OpenCV
- NumPy
- Image Processing


## 📈 Roadmap

- **Phase 1** – Dataset Preparation & Initial Model ✔
- **Phase 2** – Multi-surface Road Detection
- **Phase 3** – Real-time Deployment
- **Phase 4** –  Navigation Dashboard

## 📌 Academic Transparency

This organization maintains:

- Structured issue tracking
- Milestone-based progress
- Pull request approvals
- Contribution logs
- Weekly progress reports


## 🚀 Vision

To extend **Safe-Roads** into a scalable ML-Based solution capable of supporting ** Road monitoring systems**.
