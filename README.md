# Object-Detection-in-Satellite-Imagery-for-Environmental-Monitoring
Developed a deep learning model using Faster R-CNN to detect and classify environmental objects such as animals, vehicles, and buildings in satellite imagery. Preprocessed real-world datasets using Python and trained the model on COCO and Pascal VOC images. 

# Enhancing Environmental Monitoring through Object Detection in Satellite Imagery
# Code implementation in Google Colab
https://colab.research.google.com/drive/1dsXydoxsArHEw7XZ_w_dzWy3l4JS2MFp?usp=sharing


## 🌍 Project Overview
This project explores the application of deep learning-based object detection models to improve environmental monitoring using satellite imagery. Implemented as part of the Computer Vision and AI module in the MSc Data Analytics program, the project focused on detecting animals, vehicles, and human-related objects in remote locations using high-resolution satellite data.

## 🔍 Problem Statement
Traditional satellite monitoring techniques struggle with real-time object recognition and often lack the accuracy needed for environmental applications. To overcome this, we adopted modern object detection architectures like **Faster R-CNN** to automate the identification of objects in complex satellite imagery.

## 🧠 Key Features
- Collected and preprocessed datasets using **Pascal VOC** and **COCO** via Python.
- Applied **normalization**, **image augmentation**, and **resizing** to enhance model robustness.
- Implemented **Faster R-CNN** using **TensorFlow**, evaluating model performance using **mAP**, **precision**, and **recall**.
- Visualized detection outputs and compared model results with state-of-the-art alternatives.
- Assessed the practical impact on wildlife tracking, deforestation detection, and vehicle surveillance.

## 🛠️ Tools & Technologies
Python · TensorFlow · Keras · Faster R-CNN · OpenCV · Satellite Imagery · Google Colab · Matplotlib

## 📊 Performance Metrics
- Mean Average Precision (mAP): 0.82
- Precision: 85%
- Recall: 78%
- Demonstrated real-world use cases through examples in satellite analysis.

## 📁 Dataset Used
- [COCO Dataset](https://cocodataset.org/)
- [Pascal VOC Dataset](https://host.robots.ox.ac.uk/pascal/VOC/)

## 📍 Future Scope
- Extend to multi-class detection using **YOLOv5**
- Apply semantic segmentation for terrain mapping
- Integrate with geospatial mapping tools like QGIS for enhanced visualization

## 📌 Learning Outcomes
- Applied CNN-based object detection in environmental scenarios.
- Understood model tuning, evaluation, and scalability challenges.
- Explored the intersection of AI and sustainability.
