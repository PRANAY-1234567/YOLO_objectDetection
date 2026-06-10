# 🎯 YOLOv8 Webcam Object Detection
Real-time object detection using **YOLOv8** and your webcam. This project leverages **Ultralytics YOLOv8** for detection and **OpenCV** for video capture and display.

--

## 📌 Overview

This project captures live video from your webcam and performs **frame-by-frame object detection** using a pre-trained YOLOv8 model. Detected objects are displayed with bounding boxes and labels in real time.

---

## 🚀 Features

* 🔴 Real-time object detection via webcam
* ⚡ Uses lightweight **YOLOv8n** model (fast & efficient)
* 🧩 Simple, beginner-friendly Python implementation
* ⌨️ Press **`q`** to exit detection window
* 📦 Easily switch between different YOLOv8 models

---

## 🛠️ Tech Stack

* **Python**
* **OpenCV (cv2)**
* **Ultralytics YOLOv8**

---

## 📂 Project Structure

```
yolov8-webcam-detection/
│── detect_webcam.py
│── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/yolov8-webcam-detection.git
cd yolov8-webcam-detection
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

* **Linux/Mac**

```bash
source venv/bin/activate
```

* **Windows**

```bash
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install ultralytics opencv-python
```

---

## ▶️ Usage

Run the script:

```bash
python detect_webcam.py
```

### 🎥 What Happens

* Webcam starts automatically
* Each frame is processed using YOLOv8
* Detected objects appear with:

  * Bounding boxes
  * Labels

Press **`q`** to exit the application.

---

## 🧠 How It Works (Quick Explanation)

* Loads YOLO model:

  ```python
  YOLO('yolov8n.pt')
  ```
* Captures webcam feed:

  ```python
  cv2.VideoCapture(0)
  ```
* Runs detection on each frame
* Displays annotated frames using OpenCV

---

## 📸 Output

* Real-time video stream
* Objects detected with:

  * Labels
  * Confidence scores
  * Bounding boxes

---

## 📦 Model Options

You can switch models depending on performance needs:

| Model   | Speed     | Accuracy  |
| ------- | --------- | --------- |
| yolov8n | ⚡ Fastest | Low       |
| yolov8s | Fast      | Medium    |
| yolov8m | Moderate  | High      |
| yolov8l | Slow      | Very High |

👉 Change model in code:

```python
model = YOLO('yolov8s.pt')
```

---

## 🚀 Future Improvements

* 🎥 Add video file detection support
* 💾 Save output video
* 🧠 Train custom model (custom dataset)
* 📊 Display FPS counter
* 🖥️ Add GUI interface

---

## 🧪 Sample Enhancement (Optional)

Add FPS counter:

```python
import time
start = time.time()
# process frame
end = time.time()
fps = 1 / (end - start)
print(f"FPS: {fps:.2f}")
```

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Pranay Jadhao**
Electronics & Telecommunication Engineer
Aspiring Software & Embedded Systems Engineer

---

## ⭐ Support

If you found this project helpful:

* ⭐ Star this repository
* 🍴 Fork it
* 🧠 Build something cool with it

---

💡 *Tip: This project is great to showcase on your resume for computer vision roles.*

![image](https://github.com/user-attachments/assets/30c761d3-085f-49c0-b30b-c3073ab9a103)
