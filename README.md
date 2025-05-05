# 🖼️ Object Extraction using Thresholding Techniques

This project demonstrates how to extract objects from a homogeneous background using various **image thresholding** methods in Python with OpenCV.

## 📌 Objective

To apply different thresholding techniques to segment and extract an object from its background. The goal is to isolate the object using methods such as:
- Binary Thresholding
- Otsu's Thresholding
- Adaptive Thresholding

## 🧰 Tools & Libraries Used

- Python
- OpenCV
- Matplotlib
- Jupyter Notebook
- VS Code

## 🖼️ Input

- A single image (`object.jpeg`) with an object placed on a plain, homogenous background.

## 🧪 Process Overview

1. Load and display the original image.
2. Convert the image to grayscale.
3. Apply various thresholding techniques:
   - Simple Binary Threshold
   - Otsu's Threshold
   - Adaptive Threshold
4. Use the best threshold (adaptive) to create a mask.
5. Apply the mask to extract the object from the original image.
6. Optionally save the final output with a transparent background.

## ✅ Output

- Extracted object image (`object_transparent.png`)
- Python Jupyter notebook (`Object_Extraction_Thresholding.ipynb`)

## 📁 Folder Structure

