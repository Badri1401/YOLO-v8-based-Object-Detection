# 🚗 YOLO-v8-based Object Detection

This project demonstrates **real-time detection** of **cars**, **pedestrians**, **traffic signs**, and other **road obstacles** using a powerful **YOLOv8** (You Only Look Once v8) deep learning model. It is designed for use in **autonomous driving**, **smart surveillance**, and **intelligent traffic systems** where both speed and accuracy are crucial.

---

## 📂 Project Structure

The repository contains the following main files:

- `car_object_detection.ipynb` – Notebook for training and testing YOLOv8 on vehicle-related datasets.
- `image_processing.ipynb` – Preprocessing and visualization notebook for image enhancement, annotation conversion, and analysis.

---

## 📊 Datasets Used

### 1. 🧠 Main Dataset – [BDD100K Dataset by solesensei](https://www.kaggle.com/datasets/solesensei/solesensei_bdd100k?resource=download)
- A large-scale driving dataset covering diverse driving scenarios.
- Includes annotations for cars, traffic lights, pedestrians, lanes, and more.
- Ideal for real-world autonomous driving simulation and model training.

### 2. 🚘 Supplementary Dataset – [Car Object Detection Dataset](https://www.kaggle.com/datasets/sshikamaru/car-object-detection)
- Focuses specifically on **car detection** from annotated images.
- Helpful for fine-tuning and transfer learning.

---

## ⚙️ Model: YOLOv8

YOLOv8 is the latest version in the YOLO family, known for:
- 💡 Real-time object detection with low latency.
- 🔍 Improved accuracy on small and medium-sized objects.
- 🧠 Easy integration with pre-trained weights and custom training.

---

## 🚀 How to Run

1. Clone the repository:
   git clone https://github.com/sourabh5657/YOLO-v8-based-Object-Detection.git
   cd YOLO-v8-based-Object-Detection

Install dependencies:
pip install ultralytics opencv-python matplotlib numpy

Run the notebooks:
Start with image_processing.ipynb to prepare data.
Use car_object_detection.ipynb to train or infer with YOLOv8.
