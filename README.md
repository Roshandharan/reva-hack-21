# Face Mask Detection Project

**Author:** Roshan Dharan Shashidharan  
**Status:** Undergraduate Project  

A deep learning-based system for detecting whether people are wearing face masks in images or video streams. This project aims to support public health measures by automatically identifying mask compliance in real-time environments.

---

## Table of Contents

- [Introduction](#introduction)  
- [Features](#features)  
- [Technology Stack](#technology-stack)  
- [Usage](#usage)  
- [Dataset](#dataset)  
- [Model Architecture](#model-architecture)  
- [Results](#results)  
- [Future Work](#future-work)  
- [References](#references)  

---

## Introduction

With the global emphasis on health and safety during pandemics, monitoring mask compliance has become crucial. This project implements a computer vision system using deep learning models to detect whether individuals in images or video streams are wearing face masks.

---

## Features

- Detects face masks in real-time from webcam feed or video files.  
- Classifies into **Mask** and **No Mask** categories.  
- Displays bounding boxes around detected faces with corresponding labels.  
- Can be extended to CCTV or public area monitoring.

---

## Technology Stack

- **Programming Language:** Python  
- **Libraries & Frameworks:**  
  - OpenCV (image processing & video capture)  
  - TensorFlow / Keras (deep learning model)  
  - NumPy & Pandas (data handling)  
  - Matplotlib / Seaborn (visualizations)  
- **Model Type:** Convolutional Neural Network (CNN)  
- **Data Formats:** Images (.jpg, .png), Video (.mp4, .avi)

---

## Usage

**Run on Images:**  
```bash
python detect_mask_image.py --image path/to/image.jpg
