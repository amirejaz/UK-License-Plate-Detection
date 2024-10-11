# UK-License-Plate-Detection
This project implements a real-time license plate detection and recognition system, specifically designed for UK-based license plates. Using YOLOv8 for object detection and custom-trained models for license plate extraction, the system detects vehicles, zooms in on license plates, and reads the plate numbers in real-time.

🚀 Features:
Vehicle Detection: Identifies vehicles in video streams with high accuracy.
UK License Plate Detection: Zooms in and isolates UK-based license plates.
License Plate Recognition: Extracts and overlays the license plate text onto the video.
Real-Time Processing: Efficiently processes video streams for instant results.
CSV Output: Saves detection results (bounding boxes and license plate text) in a CSV file.

🔧 Technologies:
YOLOv8 for vehicle and license plate detection.
OpenCV for video processing and image handling.
SORT Algorithm for vehicle tracking.
OCR for reading license plate text from images.
NumPy for efficient data manipulation.



💻 Usage:
Clone the repository.
Install the required dependencies: pip install -r requirements.txt
Run the detection script: python main.py
View the output video with detected vehicles and license plates saved as output.mp4.
