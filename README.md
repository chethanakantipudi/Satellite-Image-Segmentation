# 🛰️ Satellite-Image-Segmentation

This repository contains an end-to-end pipeline for **satellite image segmentation and object extraction** from noisy images. The project evaluates multiple segmentation techniques, including **K-Means, Mean Shift, and Graph-Based segmentation**, followed by **region-growing algorithms and connected component analysis (CCA) for refinement**.

---

## 🚀 Project Overview

Satellite images often contain noise, making object extraction challenging. This project implements:
- **Noise Reduction** using Gaussian & Median Filtering.
- **Segmentation Methods**: K-Means, Mean Shift, and Graph-Based segmentation.
- **Refinement**: Region Growing & Connected Component Analysis (CCA).
- **Evaluation Metrics**: IoU, Dice Score, and Pixel Accuracy.
- **Visualization**: Comparison of segmentation results at different stages.

---

## 💂️🏼 Folder Structure

```
📺 Satellite-Image-Segmentation
│-- 📁 Dataset/                     # EuroSAT dataset (RGB)
│-- 📁 Filtered_Images/             # Images after noise reduction
│-- 📁 Segmented_Images/            # K-Means, Mean Shift, Graph-Based segmentation outputs
│-- 📁 Refined_Objects/             # Results after Region Growing & CCA
│-- 📝 segmentation.py              # Code for segmentation methods
│-- 📝 refinement.py                # Code for region growing & CCA
│-- 📝 evaluation.py                # Code for evaluating IoU, Dice, and Pixel Accuracy
│-- 📝 visualize_results.py         # Code for visualizing segmentation steps
│-- 📝 requirements.txt             # Required dependencies
│-- 📝 README.md                    # Project documentation
```

---

## 🛠️ Installation & Requirements

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your_username/Satellite-Image-Segmentation.git
cd Satellite-Image-Segmentation
```

### 2️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

---

## 🔬 Methods Used

### **1️⃣ Noise Reduction**
- **Gaussian Filtering**
- **Median Filtering**

### **2️⃣ Segmentation Techniques**
- **K-Means Clustering**
- **Mean Shift Segmentation**
- **Graph-Based Segmentation** (Felzenszwalb’s Algorithm)

### **3️⃣ Refinement Techniques**
- **Region Growing Algorithm**
- **Connected Component Analysis (CCA)** to remove small noisy regions.

---

## 📊 Evaluation Metrics
- **IoU (Intersection over Union)**
- **Dice Score**
- **Pixel Accuracy**

---

## 🖼️ Results Visualization

We visualize segmentation results at **four stages**:
1. **Original Image** (No Noise Reduction)
2. **After Noise Reduction** (Gaussian Blur)
3. **After K-Means Segmentation**
4. **Final Refined Segmentation** (Region Growing + CCA)
