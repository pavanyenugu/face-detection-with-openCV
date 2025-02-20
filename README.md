
# Face Detection using OpenCV

This project implements face detection using OpenCV, a popular open-source computer vision library. The project uses the Haar Cascade Classifier, a pre-trained model, to detect faces in images. The project demonstrates the basic concept of face detection and can be further extended to real-time detection using a webcam.

## Technologies Used

- **Python**: A programming language used for this project.
- **OpenCV**: A library for computer vision tasks, such as face detection.
- **NumPy**: A library for numerical operations in Python.
- **Matplotlib**: A library for displaying images.

## Installation

1. **Clone this repository**:

   ```bash
   git clone https://github.com/pavanyenugu/face-detection-with-openCV.git
   cd face-detection-with-openCV
   ```

2. **Install the required libraries**:

   The required libraries are:
   - `opencv-python`
   - `numpy`
   - `matplotlib`

   To install the dependencies, run:

   ```bash
   pip install opencv-python opencv-python-headless numpy matplotlib
   ```

3. **Download the pre-trained Haar Cascade Classifier**:

   The project uses the Haar Cascade Classifier for face detection. Download the model with the following command:

   ```bash
   wget -O haarcascade_frontalface_default.xml https://github.com/opencv/opencv/raw/master/data/haarcascades/haarcascade_frontalface_default.xml
   ```

   The model will be saved as `haarcascade_frontalface_default.xml` in the current directory.

## How to Use

1. **Upload your image**:
   Place an image file (preferably with a clear view of faces) in the same directory as the script or upload it to Google Colab.

2. **Run the script**:
   In your terminal or Google Colab, run the Python script to detect faces:

   ```bash
   python face_detection.py
   ```

   The script will load the image, convert it to grayscale, apply the Haar Cascade model to detect faces, and display the image with green rectangles drawn around the detected faces.

3. **Output**:
   The output will be the same image with rectangles drawn around the detected faces.

## Project Structure

```
FaceDetection-OpenCV/
│
├── face_detection.py             # Main Python script for face detection
├── haarcascade_frontalface_default.xml  # Haar Cascade Classifier model
└── README.md                     # This README file
```


