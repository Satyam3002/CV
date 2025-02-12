# 🌿 Disease Identification through Deep Learning Classification  

## 📌 Objective  
This project focuses on identifying plant diseases using deep learning classification models. Two datasets—Plant Village (RGB) and Thermal Images—are utilized for training, validation, and testing. The goal is to evaluate multiple deep learning architectures and their effectiveness in classifying plant diseases.  

---  

## 📂 Dataset Information  

1. **Plant Village (RGB) Dataset**  
   - [Dataset Link](https://github.com/spMohanty/PlantVillage-Dataset)  
   - Contains **38 classes** of diseased and healthy plant images in RGB format.  

2. **Thermal Images Dataset**  
   - [Dataset Link](https://www.kaggle.com/sujaradha/thermal-images-diseased-healthy-leaves-paddy)  
   - Captures diseased and healthy plant leaves using thermal imaging.  

---  

## 🧠 Deep Learning Models Used  
The following deep learning architectures are explored for disease classification:  

✅ **UNet**  
✅ **ResNet**  
✅ **SegNet**  
✅ **GoogleNet**  
✅ **VGG**  
✅ **AlexNet**  
✅ **Inception V3**  
✅ **R-CNN**  
✅ **YOLOv11**  
✅ **ViT (Vision Transformer)**  
✅ **EfficientNetV2**  

---  

## ⚡ Experiments  

### 🔬 **Experiment 1: Disease Classification Performance**  
- **Dataset Splitting:**  
  - 60% Training  
  - 20% Validation  
  - 20% Testing  
- **Tasks:**  
  - Train multiple deep learning models on the datasets.  
  - Evaluate classification accuracy on the test dataset.  
  - Generate visualizations:  
    - Training and validation accuracy curves.  
    - Precision-Recall (PR) curves for model comparison.  

### 🖼️ **Experiment 2: Data Augmentation for Thermal Images**  
- **Challenge:**  
  - The thermal dataset has an imbalance in class distribution and a lower number of images.  
- **Solution:**  
  - Apply augmentation techniques such as flipping, rotation, scaling, and color adjustments.  
  - Train models with augmented images to enhance classification performance.  

---

