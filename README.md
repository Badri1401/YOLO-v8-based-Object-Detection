🚗 YOLOv8-Based Object Detection
This project demonstrates real-time detection of cars, pedestrians, traffic signs, and other road obstacles using the YOLOv8 (You Only Look Once v8) deep learning model. It is designed for use in autonomous driving, smart surveillance, and intelligent traffic systems where both speed and accuracy are crucial.

📂 Project Structure
The repository contains the following main files:

car_object_detection.ipynb – Notebook for training and testing YOLOv8 on vehicle-related datasets.

image_processing.ipynb – Preprocessing and visualization notebook for image enhancement, annotation conversion, and analysis.

car_pedestrian_detection.ipynb – Dedicated notebook for detecting cars and pedestrians with visual results and evaluation metrics.

results/ – Contains predicted images, confusion matrices, F1 scores, and evaluation outputs.

📊 Datasets Used
1. 🧠 BDD100K Dataset (by solesensei)
A large-scale driving dataset covering diverse real-world scenarios.

Includes annotations for cars, traffic lights, pedestrians, lanes, etc.

Ideal for autonomous driving simulation and model training.

2. 🚘 Car Object Detection Dataset
Focused dataset for car detection from annotated images.

Useful for fine-tuning and transfer learning specific to vehicles.

3. 🌐 Roboflow Vehicle Detection Dataset
Roboflow Vehicle Detection Dataset (6 Classes)

Contains annotations for:

Car

Two-wheeler

Bus

Pedestrian

Van

Others

Perfect for multi-class vehicle detection tasks and traffic monitoring systems.

⚙️ Model: YOLOv8
YOLOv8 is the latest in the YOLO family, known for:

💡 Real-time object detection with low latency.

🔍 High accuracy on small and medium-sized objects.

🧠 Seamless integration with pre-trained weights and custom training pipelines.

🚀 How to Run
Clone the Repository:
git clone https://github.com/Sourabh5657/YOLO-v8-based-Object-Detection.git
cd YOLO-v8-based-Object-Detection

Install Dependencies:
pip install ultralytics opencv-python matplotlib numpy pandas
Run the Notebooks:

Start with image_processing.ipynb for data preparation and annotation conversion.

Use car_object_detection.ipynb or car_pedestrian_detection.ipynb to train/infer with YOLOv8.

View predicted images, confusion matrices, and performance metrics in the results/ section.
