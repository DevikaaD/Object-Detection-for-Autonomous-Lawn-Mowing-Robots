# Object-Detection-for-Autonomous-Lawn-Mowing-Robots

## 📌 Project Overview  
This project focuses on developing an **object detection system** to enhance the efficiency and safety of **autonomous lawn mowing robots**. Using **computer vision and deep learning**, we trained models to detect various objects in an open lawn environment, ensuring precise navigation and obstacle avoidance.  

## 🎯 Objective  
- Develop an object detection system for robotic lawn mowers.  
- Annotate images using **CVAT** and train deep learning models.  
- Compare **YOLO (You Only Look Once)** for real-time performance.  
- Optimize model accuracy through **hyperparameter tuning and data augmentation**.

## 📊 Dataset  
- **800+ images** annotated using **CVAT** in YOLO format.  
- Objects detected: **benches, tree logs, tree trunks, garbage bins, rocks, poles**.  
- **Files:**  
  - Images: `.jpg`  
  - Annotations: `.txt` (YOLO format)  

## 🚀 Implementation  
### YOLO (You Only Look Once)  
- **Preprocessing:** Downloaded YOLO annotation images from CVAT.  
- **Model Training:** Used **YOLOv8** for object detection.  
- **Evaluation:** Measured accuracy and speed for real-time applications.
