# Rice-Quality-Detection-Using-Computer-Vision
This repository contains Python code for detecting the quality of rice using computer vision techniques.

## Description

The script utilizes OpenCV library functions to access the camera, capture frames, process images, and analyze rice grain quality based on aspect ratios.

## Features

- Accesses the camera to capture live images.
- Applies image processing techniques like thresholding, filtering, erosion, dilation, and edge detection.
- Analyzes aspect ratios to classify rice grains as broken or good quality.
- Provides visualizations of different stages of image processing.

## Requirements

- Python 3.x
- OpenCV (cv2)
- NumPy
- Matplotlib

## Usage

Simply run the Python script `rice_quality_detection.py`.

## Results

The program displays processed images showcasing various stages of image transformation and provides information about the total number of rice grains, broken rice grains, whole rice grains, and the percentage of whole rice grains.
