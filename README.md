YOLOv8 Webcam Object Detection 🎯
This project demonstrates real-time object detection using YOLOv8 with a webcam.
It uses OpenCV for video capture and display, and Ultralytics YOLOv8 for object detection.

📌 Features

Real-time object detection using webcam

Uses pre-trained YOLOv8n model

Simple and beginner-friendly Python code

Press q to exit detection window

🛠️ Technologies Used

Python

OpenCV (cv2)

Ultralytics YOLOv8

📂 Project Structure
├── detect_webcam.py
├── README.md

⚙️ Installation

1️⃣ Clone the repository
git clone https://github.com/your-username/yolov8-webcam-detection.git
cd yolov8-webcam-detection

2️⃣ Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # For Linux/Mac
venv\Scripts\activate      # For Windows

3️⃣ Install dependencies
pip install ultralytics opencv-python

▶️ How to Run
Run the Python script:

python detect_webcam.py

Webcam will start automatically

Detected objects will be shown with bounding boxes

Press q to quit

🧠 Code Explanation (Short)

Loads YOLOv8 model using YOLO('yolov8n.pt')

Captures video using cv2.VideoCapture(0)

Performs object detection frame-by-frame

Displays annotated frames in real time

📸 Output Example
Real-time detection with labeled objects

Bounding boxes around detected items

📦 Model Used
YOLOv8n (Nano) – lightweight & fast
You can replace it with:

yolov8s.pt

yolov8m.pt

yolov8l.pt

🚀 Future Improvements

Add video file detection

Save output video

Custom object training

FPS counter

👨‍💻 Author
Pranay Jadhao

Electronics & Telecommunication Engineer

Aspiring Software & Embedded Systems Engineer

![image](https://github.com/user-attachments/assets/30c761d3-085f-49c0-b30b-c3073ab9a103)
