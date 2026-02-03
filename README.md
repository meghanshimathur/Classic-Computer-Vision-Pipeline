Classic Computer Vision Pipeline 

This repository demonstrates a **traditional computer vision workflow** implemented using **OpenCV and Python**.  
The project focuses on feature-based image analysis without deep learning, using well-established computer vision techniques.

---

📌 Project Overview

The notebook walks through a complete **classic CV pipeline**, including:

- Image preprocessing
- Feature extraction using ORB
- Feature matching between images
- Visualization of matches
- Non-Maximum Suppression (NMS) for bounding box refinement

This project is ideal for understanding **core computer vision fundamentals**.

---

⚙️ Pipeline Steps

1. Image Preprocessing
   - Grayscale conversion
   - Noise reduction
   - Image enhancement

2. Feature Detection & Description
   - ORB (Oriented FAST and Rotated BRIEF)
   - Keypoint detection
   - Binary descriptor extraction

3. Feature Matching
   - Brute Force Matcher
   - Hamming distance
   - Sorting matches by similarity

4. Match Visualization
   - Drawing keypoint correspondences
   - Visual similarity analysis

5. Non-Maximum Suppression (NMS)
   - Removal of overlapping bounding boxes
   - Retaining highest-confidence detections

---
🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook

