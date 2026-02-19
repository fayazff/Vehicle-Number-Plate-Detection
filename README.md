# Vehicle Number Plate Detection Using Image Processing

---

## Overview

Academic mini project focused on detecting and recognizing vehicle number plates from images using image processing and OCR-based techniques.

The system extracts the license plate region and converts it into readable text format.

---

## Problem Statement

Automatic recognition of vehicle number plates is challenging due to:

- Variations in font and size (especially in India)
- Lighting conditions
- Skewed or angled images
- Noise and background interference

The goal is to build a system capable of accurately detecting and recognizing number plates under controlled conditions.

---

## Approach

- Converted RGB image to grayscale
- Applied noise reduction (Gaussian / Median filtering)
- Performed edge detection
- Extracted plate region using contour analysis
- Segmented individual characters
- Applied template matching / OCR for character recognition

---

## System Pipeline

1. Input Image  
2. Image Preprocessing  
3. Plate Region Extraction  
4. Character Segmentation  
5. Feature Extraction  
6. Character Recognition  

---

## Tech Stack

- Python
- OpenCV
- Optical Character Recognition (OCR)
- Image Processing Techniques

---

## Results

- Successfully detects number plates under proper lighting
- Works best with frontal (90°) images
- Recognition accuracy depends on image clarity

---

## Limitations

- Sensitive to low-light conditions
- Reduced performance for tilted plates
- Requires good image resolution

---

## Future Improvements

- Implement CNN-based detection models
- Improve robustness under poor lighting
- Enable real-time detection
- Train on larger and diverse datasets

---

## Repository Contents

- Project Report (PDF)
- Documentation

(No executable source code included)
