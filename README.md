# Historic Document Segmentation

## Overview

This project focuses on segmenting characters from historical Modi script documents using image processing techniques. The pipeline identifies vowels, consonants, and matras and generates bounding boxes for each segmented component.

## Problem Statement

Historical document digitization is challenging because of:

* Noise and degradation
* Touching characters
* Complex script structures
* Variations in handwriting

The objective is to automatically segment character regions for downstream OCR applications.

## Methodology

1. Image preprocessing

   * Grayscale conversion
   * Noise removal
   * Thresholding

2. Shirorekha Removal

   * Detects and removes header lines

3. Character Segmentation

   * Connected component analysis
   * Contour detection
   * Bounding box generation

4. Classification Preparation

   * Segmented characters stored for OCR training

## Results

* Successfully segmented Modi script characters
* Generated bounding boxes around character regions
* Improved character isolation for OCR pipelines

## Tech Stack

* Python
* OpenCV
* NumPy
* Matplotlib

## Future Improvements

* Deep Learning-based segmentation
* Integration with OCR models
* Historical manuscript restoration
* Automated character recognition


