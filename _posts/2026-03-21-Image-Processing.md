---
title: 'Image Processing'
date: 2026-03-21
permalink: /posts/Image-Processing/
tags:
  - Computer Vision
  - Image Segmentation
  - Feature Detection
  - Morphological Operations
  - Harris Corner Detection
  - SIFT
  - Python
---

A comprehensive collection of hands-on projects in image processing covering fundamental and advanced techniques, implemented in Python with Jupyter notebooks.

## Sessions Overview

| Session  | Topic                     | Key Techniques                                                                 |
| -------- | ------------------------- | ------------------------------------------------------------------------------ |
| **BE 1** | Thresholding & Morphology | Binary segmentation, morphological operators, image cleanup                    |
| **BE 2** | Geometric Transformations | Forward/backward mapping, coordinate systems, interpolation methods            |
| **BE 3** | Feature Detection         | Harris corner detection, scale-space blob detection, feature matching          |
| **BE 4** | Bag of Visual Words       | SIFT, KMeans clustering, TF-IDF, spatial pyramid pooling, image classification |

## Key Concepts

- **Image Segmentation**: thresholding strategies, morphological operations, region-growing algorithms
- **Geometric Vision**: coordinate transformations, image warping with bilinear interpolation, evaluation metrics (MSE, PSNR, SSIM)
- **Feature Extraction**: Harris corner response, eigenvalue analysis, scale-invariant keypoint detection
- **Visual Recognition**: building BoVW pipelines from scratch, vocabulary learning, similarity-based retrieval, SVM classification

## Quick Start

**Requirements:**
- Python 3.8+
- See `requirements.txt` or install:

```bash
pip install numpy matplotlib scikit-image opencv-python scikit-learn scipy pandas jupyter
```

**Run the notebooks:**

Open any notebook in `BE_session_*/` and execute cells top-to-bottom.

## Repository Structure

```
.
├── BE_session_1/
│   ├── BE-Thresholding-Morphology-Student.ipynb
│   ├── Images/
│   └── defects/
├── BE_session_2/
│   ├── TD2_login1_login_2.ipynb
│   ├── parrot.jpg
│   └── ground_truth.npy
├── BE_session_3/
│   ├── BE3_login1_login_2.ipynb
│   └── [test images]
├── BE_session_4/
│   ├── BE4_BoVW_student1_student2.ipynb
│   └── TD4-Student/data-BE4/
│       ├── breastmnist_128.npz
│       └── SUN/ (10-class scene subset)
└── README.md
```

## Technologies Used

- **Image Processing**: scikit-image, OpenCV (cv2)
- **Numerical Computing**: NumPy, SciPy
- **Machine Learning**: scikit-learn (KMeans, SVM)
- **Visualization**: Matplotlib
- **Development**: Jupyter Notebooks