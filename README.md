# Near Duplicate Image Detection

This project provides a Python-based solution for detecting duplicate and near-duplicate images using gradient-based feature extraction, hashing, and Hamming distance. It is designed for efficient and robust image comparison, even for large datasets.

## Features
- **Grayscale Conversion**: Simplifies image data by converting it to grayscale.
- **Image Resizing**: Standardizes images to a fixed resolution for consistent comparisons.
- **Gradient-Based Descriptors**: Uses intensity differences to generate unique binary descriptors.
- **Hashing for Fast Comparison**: Employs MD5 hashing to detect exact duplicates.
- **Hamming Distance for Similarity**: Identifies near-duplicate images based on binary descriptor similarity.

## Requirements
- Python 3.x
- NumPy
- OpenCV
- Matplotlib
- SciPy

## Usage
1. Place your images in the specified directory.
2. Run the script to preprocess images, extract features, and detect duplicates.
3. View duplicate images side-by-side in the output.

## Installation
Clone the repository and install the required dependencies:
```bash
git clone https://github.com/tstazbid/near-duplicate-images-detection.git
