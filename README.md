# Machine Vision — University of Tehran

This repository contains my coursework and implementations for the **Machine Vision** course at **University of Tehran (Semester 4041)**.

The assignments cover a range of computer vision concepts, from fundamental image processing and feature detection to 3D reconstruction, camera calibration, color spaces, and object tracking. Each assignment includes a Jupyter Notebook with the corresponding implementation and experiments.

Each assignment folder also contains a dedicated `README.md` with a more detailed description of its implementation, experiments, and results.

## Table of Contents

- [Assignments](#assignments)
  - [Assignment 1 — Image Processing Fundamentals](#assignment-1--image-processing-fundamentals)
  - [Assignment 2 — Feature Detection and Image Matching](#assignment-2--feature-detection-and-image-matching)
  - [Assignment 3 — 3D Reconstruction and Camera Calibration](#assignment-3--3d-reconstruction-and-camera-calibration)
  - [Assignment 4 — Color Spaces and Feature Tracking](#assignment-4--color-spaces-and-feature-tracking)
- [Repository Structure](#repository-structure)
- [Technologies](#technologies)
- [Topics Covered](#topics-covered)

## Assignments

### Assignment 1 — Image Processing Fundamentals

The first assignment focuses on **fundamental image processing techniques** and their applications in image enhancement, analysis, and restoration.

The implementation includes:

- Min-Max and percentile contrast stretching.
- Histogram equalization using the cumulative distribution function.
- 2D Fourier transform and phase/magnitude analysis.
- Gaussian filtering, Sobel gradients, and non-maximum suppression for Canny edge detection.
- Gaussian and Laplacian image pyramids.
- Frequency-domain periodic noise removal using notch reject filters.

**Notebook:** [Assignment1.ipynb](Assignment1/Assignment1.ipynb)

### Assignment 2 — Feature Detection and Image Matching

The second assignment explores **feature detection, geometric line detection, and image matching**.

The implementation includes:

- Hough Transform for line detection, implemented from scratch.
- SIFT keypoint and descriptor extraction.
- Face recognition using descriptor matching and distance thresholds.
- Rank-1 and Rank-14 recognition evaluation.
- Harris corner detection and feature matching.
- Image stitching using homography estimation and RANSAC.

**Notebook:** [Assignment2.ipynb](Assignment2/Assignment2.ipynb)

### Assignment 3 — 3D Reconstruction and Camera Calibration

The third assignment focuses on **stereo vision and camera calibration** to recover 3D information from images.

The implementation includes:

- SIFT feature detection and matching between stereo images.
- Fundamental matrix estimation using RANSAC.
- Camera matrix construction and epipolar geometry visualization.
- Triangulation and relative depth estimation.
- Checkerboard corner detection and refinement.
- Camera intrinsic and extrinsic parameter estimation using OpenCV calibration.
- Reprojection-based calibration evaluation.

**Notebook:** [Assignment3.ipynb](Assignment3/Assignment3.ipynb)

### Assignment 4 — Color Spaces and Feature Tracking

The fourth assignment covers **color representation, skin-color segmentation, and motion analysis in video sequences**.

The implementation includes:

- RGB channel visualization and an introduction to the CIE XYZ color space.
- Manual RGB-to-HSV and RGB-to-Y'CbCr conversions.
- Grayscale conversion using weighted RGB components.
- Normalized RGB and face segmentation using color-based masking.
- Shi–Tomasi corner detection and Lucas–Kanade optical flow tracking.
- Camera motion estimation using affine transformations and RANSAC.
- Separation of background-motion points from independently moving points.

**Notebook:** [Assignment4.ipynb](Assignment4/Assignment4.ipynb)

## Repository Structure

```text
MV-coursework/
│
├── Assignment1/
│   ├── Assignment1.ipynb
│   ├── README.md
│   ├── imgs/
│   └── figs/
│
├── Assignment2/
│   ├── Assignment2.ipynb
│   ├── README.md
│   ├── .gitignore
│   ├── imgs/
│   └── figs/
│
├── Assignment3/
│   ├── Assignment3.ipynb
│   ├── README.md
│   ├── imgs/
│   └── figs/
│
├── Assignment4/
│   ├── Assignment4.ipynb
│   ├── README.md
│   ├── img_and_vids/
│   └── figs/
│
└── README.md
```

## Technologies

The coursework uses Python and common computer vision and scientific computing libraries, including:

- **Python**
- **Jupyter Notebook**
- **NumPy**
- **OpenCV**
- **SciPy**
- **Matplotlib**

## Topics Covered

| Assignment | Area | Topics |
|---|---|---|
| Assignment 1 | Image Enhancement | Contrast Stretching, Histogram Equalization |
| Assignment 1 | Frequency Domain | Fourier Transform, Magnitude and Phase |
| Assignment 1 | Edge Detection | Gaussian Filtering, Sobel Gradients, Canny |
| Assignment 1 | Image Pyramids | Gaussian and Laplacian Pyramids |
| Assignment 1 | Image Restoration | Notch Filtering, Periodic Noise Removal |
| Assignment 2 | Line Detection | Hough Transform, Accumulator Voting |
| Assignment 2 | Feature Detection | SIFT, Harris Corner Detection |
| Assignment 2 | Face Recognition | Descriptor Matching, Distance Thresholds, Rank-1 and Rank-14 Accuracy |
| Assignment 2 | Image Stitching | Feature Matching, Homography, RANSAC |
| Assignment 3 | Stereo Vision | Feature Matching, Fundamental Matrix, Epipolar Geometry |
| Assignment 3 | 3D Reconstruction | Camera Matrices, Triangulation, Depth Estimation |
| Assignment 3 | Camera Calibration | Checkerboard Detection, Intrinsic and Extrinsic Parameters |
| Assignment 3 | Calibration Evaluation | Reprojection Error |
| Assignment 4 | Color Spaces | RGB, XYZ, HSV, Y'CbCr, Grayscale |
| Assignment 4 | Image Segmentation | Normalized RGB, Skin-Color Detection, Masking |
| Assignment 4 | Optical Flow | Shi–Tomasi, Lucas–Kanade Tracking |
| Assignment 4 | Motion Analysis | Affine Motion Estimation, RANSAC, Moving Object Separation |

---

*Coursework completed as part of the Machine Vision course at the University of Tehran.*