# Object Detection using YOLO26 🚗🚶

My first Computer Vision and Deep Learning project using the YOLO26 model for real-time object detection.

This project was developed as part of my Deep Learning practical, but the main purpose of this repository is to document my learning journey with YOLO and understand how object detection works in real-world video.

---

## 📌 About the Project

Object detection is a computer vision task where a model identifies **what objects are present in an image or video and where they are located**.

In this project, I learned and implemented object detection using **YOLO26 (You Only Look Once)**.

The project focuses on road and traffic scenes, where objects such as:

- 🚗 Cars
- 🚌 Buses
- 🚚 Trucks
- 🏍️ Motorcycles
- 🚲 Bicycles
- 🚶 Pedestrians
- 🚦 Traffic lights
- 🛑 Stop signs

can be detected.

Along with basic detection, I also explored additional concepts such as object tracking, confidence thresholds, FPS calculation, object counting, and proximity-based warnings.

---

# 🎯 Objectives

The main objectives of this project were:

1. Understand the basic concept of object detection.
2. Learn how YOLO works at a practical level.
3. Use a pretrained YOLO model for object detection.
4. Perform object detection on images.
5. Perform object detection on videos.
6. Understand bounding boxes and confidence scores.
7. Learn how object tracking works.
8. Calculate FPS for real-time performance.
9. Count detected objects.
10. Implement a simple proximity warning system.
11. Understand the limitations of pretrained object detection models.

---

# 🧠 What I Learned

This project was mainly a learning exercise. The following are the concepts I explored.

## 1. Computer Vision

I learned how computers can process images and videos as numerical data.

An image can be represented as an array of pixel values, while a video is essentially a sequence of image frames.

```text
Image
  ↓
Pixels
  ↓
Numerical representation
  ↓
Computer Vision Model
  ↓
Prediction
