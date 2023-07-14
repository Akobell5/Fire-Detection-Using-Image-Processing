# Fire-Detection-Using-Image-Processing
This Python code utilizes OpenCV and a Haar Cascade Classifier to detect fire in real-time using a webcam. The code captures video frames from the webcam, applies image processing techniques, and identifies regions with fire-like patterns.
When fire is detected, it saves multiple frames of the fire region and displays visual indicators on the screen.

Dependencies:
numpy
cv2 (OpenCV)
Usage:
Make sure you have the necessary dependencies installed.
Place the "fire_detection.xml" file in the same directory as the code.
Run the code and ensure that a webcam is connected to your system.
The code will open a window displaying the processed video feed from the webcam.
When fire is detected, the code will save a series of frames in a folder named "detected" and indicate the presence of fire on the screen.
Press the 'ESC' key to exit the program.
Description:
The code starts by importing the required libraries and defining constants for image size and location to save the detected frames.
It loads the Haar Cascade Classifier for fire detection from the "fire_detection.xml" file.
The code initializes the webcam using OpenCV's VideoCapture function.
Inside the main loop, it continuously captures frames from the webcam and performs various image processing steps.
Gaussian blurring is applied to reduce noise in the image.
Bilateral filtering is used to enhance the edges and preserve important details.
The frame is converted to grayscale for fire detection.
The Haar Cascade Classifier is used to detect fire in the grayscale image.
If the fire is detected, it draws rectangles around the fire region, saves multiple frames of the region, and displays a message on the screen.
The processed video frame with visual indicators is displayed in a window.
Pressing the 'ESC' key terminates the program.
Additional Notes:
Ensure that the "fire_detection.xml" file is in the same directory as the code for proper functioning.
Adjust the parameters in the code, such as the scale factor and minimum neighbors, to optimize the fire detection performance.
Customize the file-saving path, image size, and any additional visual indicators as per your requirements.
Experiment with different image processing techniques and parameters to improve fire detection accuracy.
License:
This code is provided as-is without any warranties or guarantees. You are free to use and modify the code to suit your needs. Refer to the licenses of the libraries used, such as OpenCV, for more information on usage and distribution.

Please refer to the additional documentation or comments within the code for more details on the implementation and usage, also you can reach me on +2347064625756
