# Multimodal-Image-Registration

Example scripts for **image registration**: finding corresponding points between two images (for example ultrasound and CT) as a first step towards aligning them.

> Status: basic example scripts from my work on medical image registration. You can use it for clinical purpose too but read MIT license.

## What is image registration?
Registration aligns two or more images, possibly from different modalities such as ultrasound, CT or MRI, by finding a transformation that maps the pixel coordinates of one image onto the other. The usual steps are feature extraction, feature matching and transformation estimation.

## Contents
| File | What it does |
|---|---|
| `Scale-Invariant Feature Transform.py` | Detects SIFT keypoints in two images and displays them |
| `SIFT Algorithm.py` | Matches SIFT keypoints between two images and draws the best matches |

This repository contains only the SIFT feature-detection and matching examples. Transformation estimation and the full registration workflow are not included.

## Requirements
`pip install opencv-python numpy` (SIFT needs OpenCV 4.4 or newer). Set the image paths at the top of each script. No images are included, and no patient data should be uploaded.

## Use and contact
If you use, adapt or contribute to this work, please credit the author and **contact or inform me by email: owaiskhan_bangash@yahoo.com**

## Author
BEN, Software Engineer. GitHub: [Bangash514](https://github.com/Bangash514)
