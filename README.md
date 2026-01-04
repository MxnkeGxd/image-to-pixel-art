# 🚗 Car Detection using YOLOv8

This project implements a **car object detection system** using **YOLOv8 (Ultralytics)**.  
The model is trained on a custom dataset exported from **Roboflow** and is capable of detecting cars in images using bounding boxes.

---

## 📌 Features
- Object detection using **YOLOv8**
- Custom car detection dataset
- Training and inference scripts included
- CPU-based training supported
- GitHub-ready project structure

---

## 🧠 Model Used
- **YOLOv8n (Nano)** – lightweight and fast
- Transfer learning using pre-trained weights

---

## 📂 Project Structure

object-detection/
├── dataset/
│ └── data.yaml
├── yolov8_train.py
├── yolov8_infer.py
├── requirements.txt
├── README.md
└── .gitignore


*(Dataset images and training outputs are excluded from GitHub)*

---

## 📊 Dataset
- Source: **Roboflow**
- Classes:
  - `0: car`
- Format: **YOLOv8**

Dataset link:
https://roboflow.com

---

## ⚙️ Installation
```bash
pip install -r requirements.txt

Or manually:

pip install ultralytics opencv-python torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cpu

🚀 Training the Model

python yolov8_train.py

Training results are saved in:

runs/detect/

🔍 Inference (Testing)

    Place a test image as test.jpg in the project root

    Run:

python yolov8_infer.py

The model will display bounding boxes around detected cars.
📈 Results

    Successfully trained YOLOv8 model

    Cars detected with bounding boxes and confidence scores

    Model evaluated using validation dataset

🧪 Technologies Used

    Python

    YOLOv8 (Ultralytics)

    OpenCV

    PyTorch

🎓 Academic Use

This project was developed as part of a Machine Learning / Computer Vision academic project.
