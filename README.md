# Computer-Vision-Techniques-Implementation
Image Processing Techniques Using OpenCV

This project demonstrates a complete image-processing workflow using Python and OpenCV, covering 5 major computer vision techniques:

✅ Global Thresholding
✅ Binary Image Labeling
✅ Hough Line Detection
✅ Optical Flow (Farnebäck Method)
✅ Face Detection using Haar Cascade

Each module processes images from a dataset, performs a specific transformation/analysis, and saves results to an output folder.

🚀 Technologies Used

Python 3

OpenCV (cv2)

NumPy

Matplotlib

Jupyter Notebook

🧠 1. Global Thresholding
✅ Description

Global Thresholding converts grayscale images into binary (black & white) images using a fixed intensity threshold.

✅ What the Code Does

Loads images from cars_dataset/

Converts them to grayscale

Applies cv2.threshold() with threshold = 127

Saves output to global_threshold/

Displays a before–after visualization

✅ Use Cases

Object segmentation

Document scanning

OCR preprocessing

🏷️ 2. Binary Image Labeling (Contour Detection)
✅ Description

Extracts contours from binary images and draws bounding boxes + labels (Obj 1, Obj 2…).

✅ What the Code Does

Uses thresholded images

Detects contours using cv2.findContours()

Draws bounding boxes

Labels each object

Outputs images to labeled_dataset/

✅ Use Cases

Object counting

Region-of-interest detection

Dataset annotation

📏 3. Hough Line Detection
✅ Description

Detects straight lines in an image using Probabilistic Hough Transform.

✅ What the Code Does

Applies Canny Edge Detection

Detects lines using cv2.HoughLinesP()

Draws lines on original image

Saves to Hough_lines_dataset/

✅ Use Cases

Lane detection (self-driving cars)

Structural line detection

Road/edge analysis

🎥 4. Optical Flow (Farnebäck Method)
✅ Description

Calculates per-pixel motion between consecutive frames in an image sequence.

✅ What the Code Does

Loads sorted image sequence

Applies cv2.calcOpticalFlowFarneback()

Converts motion vectors to HSV color image

Saves to optical_flow_dataset/

✅ Use Cases

Video motion tracking

Traffic monitoring

Robotics & navigation

🙂 5. Face Detection Using Haar Cascade
✅ Description

Detects faces using OpenCV’s pretrained Haar Cascade Classifier.

✅ What the Code Does

Loads images from face_dataset/

Converts them to grayscale

Applies detectMultiScale()

Draws bounding boxes around faces

Saves processed images to face_detection_dataset/

✅ Use Cases

Attendance systems

Surveillance

Preprocessing for face recognition

🛠️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/Image-Processing-Project.git
cd Image-Processing-Project

2️⃣ Install Dependencies
pip install opencv-python numpy matplotlib

3️⃣ Run the Notebooks

Open Jupyter Notebook:

jupyter notebook

📌 How to Use

Place your input images in the correct folders:

cars_dataset/ → for tasks 1–4

face_dataset/ → for face detection

Open respective notebooks and run all cells.

Processed images will appear in the respective output folders.

📊 Sample Outputs

✅ Binary images
✅ Labeled objects
✅ Detected lines
✅ Motion visualization
✅ Detected faces

(Add sample images if needed.)

🧪 Project Highlights

Covers multiple OpenCV tasks in one project

Good demonstration for computer vision beginners

Clean modular structure

Ready for academic submission & viva
