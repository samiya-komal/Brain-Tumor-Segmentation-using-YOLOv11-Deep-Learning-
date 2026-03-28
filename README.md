<img width="1034" height="434" alt="image" src="https://github.com/user-attachments/assets/a899ab07-c872-4e69-bef6-425c8626bf7d" /># 🧠 Brain Tumor Segmentation using YOLOv11

## 📌 Project Overview
This project focuses on detecting and segmenting brain tumors from MRI images using the YOLOv11 segmentation model. The goal is to build an efficient deep learning model that can assist in medical image analysis.

---

## 🚀 Key Features
- Brain tumor detection and segmentation
- YOLOv11 segmentation model (Ultralytics)
- Trained on custom dataset from Roboflow
- GPU-based training (Tesla T4)
- Model evaluation using confusion matrix
- Prediction visualization on test images

---

## 🛠️ Technologies Used
- Python
- Google Colab
- Ultralytics (YOLOv11)
- Roboflow
- OpenCV
- Deep Learning (Computer Vision)

---

## 📂 Dataset
- Source: Roboflow
- Project: Brain Tumor Dataset
- Format: YOLOv11 segmentation format
- Includes labeled MRI images for training and validation

---

## ⚙️ Model Training
- Model: YOLOv11 Segmentation (`yolo11n-seg.pt`)
- Epochs: 10
- Image Size: 640x640
- Device: Tesla T4 GPU

---

## 📊 Results
- Generated confusion matrix for evaluation
- Model successfully detected tumor regions in MRI images
- Predictions saved and visualized

---

## 🔍 Sample Prediction

### 🔹 
![Training Result](training-result.png)
![Final Result](final-result.png)
![Confusion Matrix](confusion-matrix.png)



---

## ▶️ How to Run
1. Open Google Colab
2. Install dependencies:
   ```bash
   pip install ultralytics roboflow
