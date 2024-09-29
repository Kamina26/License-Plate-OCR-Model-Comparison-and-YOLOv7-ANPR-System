# License Plate OCR: Model Comparison and YOLOv7 ANPR System

This repository contains a series of Jupyter notebooks dedicated to developing and comparing Optical Character Recognition (OCR) models for license plate recognition. Additionally, it includes a YOLOv7-based Automatic Number Plate Recognition (ANPR) system designed specifically for Iranian license plates. The goal is to enhance OCR performance and evaluate multiple models to determine the most accurate approach for recognizing characters in various environmental conditions.

## Overview
Accurate recognition of vehicle license plates is crucial for applications such as traffic management, toll systems, and security. This project compares different OCR models' performance on Iranian license plates, focusing on training data from real-world scenarios. It also implements an ANPR system using the YOLOv7 architecture for object detection and OCR tasks.

## Project Structure
The repository includes the following key files:
1. **plate_OCR_comparison.ipynb**: A notebook comparing different OCR models for license plate recognition.
2. **train_plate_OCR_ir.ipynb**: A notebook dedicated to training OCR models on a dataset of Iranian license plates.
3. **Yolov7_ANPR_ir.ipynb**: A notebook implementing YOLOv7 for Automatic Number Plate Recognition.

## Installation
To use the notebooks, you will need to install the necessary dependencies. Follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/license-plate-ocr-anpr.git
   cd license-plate-ocr-anpr

required packages:
pip install -r requirements.txt

You can just open the desired notebook in Jupyter or Google Colab.
Run the cells to train models or run inference on license plate images.
For YOLOv7 ANPR, ensure you have the necessary model weights. You can download pre-trained weights from the YOLOv7 GitHub repository.
