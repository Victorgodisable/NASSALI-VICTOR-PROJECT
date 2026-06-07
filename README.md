# NASSALI-VICTOR-PROJECT

# Herbal Plant Recognition Using SIFT, BoVW and SVM

## Project Overview
This project presents a classical computer vision pipeline for herbal plant recognition using SIFT feature extraction, Bag-of-Visual-Words (BoVW) encoding, and Support Vector Machine (SVM) classification.

## Dataset
- Source: Video recordings captured under natural outdoor conditions
- Total videos: 21
- Classes used: 12 (Plant_A to Plant_L)
- Train/Test Split: 80/20

## Methodology
1. Frame Extraction (every 10th frame)
2. Image Preprocessing
   - Grayscale conversion
   - Resize to 224×224
   - Gaussian blur
   - Laplacian sharpening
3. SIFT Feature Extraction
4. BoVW Encoding (K=100)
5. SVM Model Training
6. Evaluation and Similarity Analysis

## Results
- Test Accuracy: 86.8%
- Weighted F1-score: 0.86

## Technologies Used
- Python
- OpenCV
- Scikit-learn
- NumPy
- Matplotlib

## Author
Nassali Victor
Bachelor of Computer Science
Ndejje University
