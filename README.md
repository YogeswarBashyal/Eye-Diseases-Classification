# Eye Disease Classification using MobileNetV3 + Grad-CAM

This project implements a **Deep Learning model** for **Eye Disease Detection** using **Transfer Learning with MobileNetV3Small**.  
It classifies retinal fundus images into four disease categories and visualizes important regions using **Grad-CAM**.

---

### Diseases Covered
- **Cataract**
- **Diabetic Retinopathy**
- **Glaucoma**
- **Normal**

### Key Features
- Transfer Learning with **MobileNetV3Small** (pretrained on ImageNet)
- **Fine-tuning** of the last 30 layers for higher accuracy
- **Class weights** for handling imbalanced datasets
- **Grad-CAM** for visual interpretability
- Training and validation **data augmentation**
- Evaluation with **classification report** and **confusion matrix**

---

## 📂 Dataset Structure

Place your dataset in this structure:

