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
│-- 📝 requirements.txt             # Required dependencies
│-- 📝 README.md                    # Project documentation
|--📜 segmentation_notebook.ipynb   # Jupyter Notebook with complete 
                                  implementation 
```

---

## 🛠️ Installation & Requirements
pip install -r requirements.txt

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/chethanakantipudi
/Satellite-Image-Segmentation.git
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

## Example visualization:

![image](https://github.com/user-attachments/assets/4c2f73f6-48de-4d8a-af59-a206437bbae0)

## 📜 License
This project is licensed under the MIT License.




