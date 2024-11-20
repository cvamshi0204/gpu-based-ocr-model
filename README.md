# Optical Character Recognition (OCR) Model and Video Frame Processing

## Overview

This project implements an Optical Character Recognition (OCR) model using Convolutional Neural Networks (CNNs). It processes video frames to classify content and measures processing efficiency on both CPU and GPU. The project includes performance visualization for frame-wise processing times.

---

## Features

1. **OCR Model:**
   - Simple CNN-based architecture.
   - Supports input images of shape `(128, 128, 3)`.
   - Configured for 10-class classification tasks.

2. **Video Frame Processing:**
   - Processes video frames through the OCR model.
   - Handles video input with batch processing.
   - Measures per-frame processing times.

3. **Performance Comparison:**
   - Evaluates and compares CPU and GPU processing efficiency.
   - Visualizes processing times for each frame.

4. **Synthetic Data Generator:**
   - Creates dummy data for model training and validation.

---

## Requirements

Ensure the following dependencies are installed:

- **Python 3.x**
- **TensorFlow 2.x**
- **OpenCV** (`cv2`)
- **NumPy**
- **Matplotlib**
