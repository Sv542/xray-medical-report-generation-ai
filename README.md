# X-Ray Medical Report Generation using Deep Learning

## Overview
This project builds an AI system that automatically generates medical reports from chest X-ray images using a deep learning encoder–decoder architecture. The system extracts visual features from X-ray images and generates structured diagnostic text, demonstrating how AI can assist clinicians by reducing manual documentation workload.

## Problem
Radiologists spend significant time analyzing medical images and writing diagnostic reports. This project explores how deep learning can help automate parts of this process by generating medical descriptions directly from X-ray images.

## Solution
The system uses a deep learning pipeline that combines computer vision and natural language generation:

1. **Feature Extraction**
   - A Convolutional Neural Network (CNN) extracts visual features from chest X-ray images.

2. **Report Generation**
   - An encoder–decoder architecture converts extracted image features into natural language medical reports.

3. **Prediction Interface**
   - A Flask web application allows users to upload an X-ray image and automatically generate a diagnostic report.

## System Architecture

X-ray Image → CNN Feature Extractor → Encoder-Decoder Model → Generated Medical Report

## Features
- Automatic medical report generation from chest X-ray images
- Deep learning model training pipeline
- TensorBoard integration for training visualization
- Flask web application for real-time predictions
- Data preprocessing and feature embedding workflow

## Tech Stack

- **Programming Language:** Python
- **Deep Learning:** PyTorch / TensorFlow
- **Web Framework:** Flask
- **Libraries:** NumPy, Pandas, Matplotlib
- **Visualization:** TensorBoard
- **Machine Learning Techniques:**
  - Convolutional Neural Networks (CNN)
  - Encoder-Decoder Architecture
  - Image Feature Embeddings
  - Natural Language Generation

## Project Structure
