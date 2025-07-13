# 🚗 Real-Time Vehicle Detection using OpenCV

This project detects vehicles in real time using a webcam and a Haar Cascade classifier in OpenCV. It captures live video, processes frames, and detects the number of cars to determine traffic conditions.

---

## 📸 Features

- 🕵️ Real-time vehicle detection using webcam
- 🧠 Pre-trained Haar Cascade classifier (`cars.xml`)
- 📊 Displays bounding boxes around detected vehicles
- 🔁 Continuously prints live traffic updates:
  - `"North More Traffic"` if cars ≥ 2
  - `"no traffic"` if cars < 2

---

## 🛠️ Technologies Used

- Python
- OpenCV (`cv2`)
- imutils
- Haar Cascade (`cars.xml`)

---

## 🧪 How It Works

1. **Capture Frame:** Uses your webcam to capture live video.
2. **Preprocess Frame:** Resizes the frame and converts it to grayscale.
3. **Detect Vehicles:** Applies a pre-trained Haar cascade classifier to detect vehicles.
4. **Display Results:** Draws rectangles around detected vehicles.
5. **Traffic Logic:** If 2 or more vehicles are detected, it prints `"North More Traffic"`; otherwise `"no traffic"`.

---
