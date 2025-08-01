# Otsu's Method for Image Thresholding

This repository contains a Jupyter Notebook that implements **Otsu's Thresholding Method**, a classical image segmentation technique used in computer vision for automatic image thresholding.

## Overview

**Otsu’s Method** automatically determines the optimal threshold value to separate foreground from background in grayscale images. This method is useful for:

- Binary image segmentation
- Preprocessing for object detection
- Medical imaging
- Document image binarization

The notebook demonstrates:
- Reading and converting images to grayscale
- Calculating image histograms
- Applying Otsu’s thresholding manually and using OpenCV
- Comparing results

## Files

- `Otsu's Method.ipynb` – Main Jupyter Notebook that implements and explains the method step-by-step.

## Requirements

Install dependencies using:

```bash
pip install opencv-python matplotlib numpy
