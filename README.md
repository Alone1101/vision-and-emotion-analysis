# Computer Vision & Emotion Analysis Pipeline

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

> **Project Context:** This pipeline was developed as a comprehensive project for the COMP3204 Computer Vision module. It traverses fundamental image processing techniques—such as image resizing with OpenCV to reduce storage, increase processing speed, and maintain uniform dimensions for machine learning models—and culminates in building real-time tracking and deep-learning-based emotion detection systems.

## Overview
This repository contains a computer vision pipeline focused on two primary tasks: real-time object tracking in video feeds (highway traffic) and facial emotion detection. The project processes video data, tracks movement, extracts emotional states, and visualizes the results.

## Features
* **Traffic Object Tracking:** Utilizes OpenCV to draw bounding boxes and track moving vehicles from a top-down highway perspective.
* **Emotion Detection:** Integrates DeepFace and TensorFlow to analyze facial expressions and log emotional states over time.
* **Data Visualization:** Parses output logs to generate clean, readable visualizations of emotion duration.

## Repository Structure
* `COMP3204_CW2.ipynb`: The main Jupyter Notebook containing the core logic, image processing, and model integration.
* `emotion_log.csv`: Raw data output logging detected emotional states over time.
* `emotion_duration_plot.png`: Bar chart visualization generated from the CSV data.
* `Task_4_Working_Screen.jpg`: Sample output frame demonstrating the vehicle tracking logic.

## Technologies Used
* Python 3
* OpenCV (cv2)
* DeepFace
* TensorFlow / Keras
* Pandas & Matplotlib
