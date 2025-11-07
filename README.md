# Image Processing Project Using OpenCV

A complete image-processing project built using **Python** and **OpenCV**, demonstrating five essential computer vision techniques:

✅ Global Thresholding  
✅ Image Labeling (Contour Detection)  
✅ Hough Line Detection  
✅ Optical Flow (Farnebäck Method)  
✅ Face Detection using Haar Cascade  

Each technique is implemented using modular Python scripts / Jupyter notebooks and produces output images for easy analysis.

---

## 📌 Project Overview

This repository showcases fundamental image-processing techniques used in computer vision. Each workflow is designed to help beginners understand how images can be segmented, labeled, analyzed for edges, tracked for motion, and scanned for faces.

The project uses two datasets:

- `cars_dataset/` → for thresholding, labeling, Hough lines, optical flow  
- `face_dataset/` → for Haar cascade face detection  

---

## 🧪 Techniques Implemented

### ✅ 1. Global Thresholding
- Converts grayscale images into binary images using a fixed threshold.
- Helps in segmentation and preprocessing.
- Implemented using `cv2.threshold()`.

### ✅ 2. Image Labeling (Object Annotation)
- Detects contours in binary images.
- Labels each object with bounding boxes and object IDs.
- Uses `cv2.findContours()` and `cv2.rectangle()`.

### ✅ 3. Hough Line Detection
- Detects straight lines using the Probabilistic Hough Transform.
- Requires Canny Edge Detection as preprocessing.
- Uses `cv2.HoughLinesP()`.

### ✅ 4. Optical Flow (Farnebäck Method)
- Calculates per-pixel motion between consecutive frames.
- Visualizes direction + magnitude using HSV color space.
- Uses `cv2.calcOpticalFlowFarneback()`.

### ✅ 5. Face Detection (Haar Cascade)
- Detects human faces using OpenCV’s pretrained Haar Cascade classifier.
- Works best for frontal faces.
- Uses `detectMultiScale()`.
## 🗂️ Project Structure

