
### 📋 Short Description

> A Python-based Face Recognition & Attendance System that detects and recognizes faces using OpenCV and records their attendance with timestamps in a CSV file.

---

### 📄 Folder Structure

```
/face-recognition-attendance/
├── face_recognition.py
├── images/
│   ├── person1.jpg
│   ├── person2.jpg
│   └── ...
├── Attendance.csv
├── README.md
```

---

### 📄 README.md

````markdown
# 👨‍🏫 Face Recognition & Attendance System

This project implements a **Face Recognition-based Attendance System** using Python.  
It captures faces in real-time from a webcam, matches them against known images, and marks attendance in a CSV file.

---

## 🚀 Features
✅ Detects and recognizes faces in real-time  
✅ Records attendance with name and timestamp  
✅ Stores attendance data in a CSV file  
✅ Uses OpenCV and face-recognition library

---

## 📂 How it Works
1️⃣ Store reference images of people in the `images/` folder.  
2️⃣ Run the script — it reads and encodes the known faces.  
3️⃣ Captures video from webcam and compares detected faces with known encodings.  
4️⃣ When a match is found, logs the name and time in `Attendance.csv`.

---

## 🧰 Technologies Used
- Python 3.x
- OpenCV
- face-recognition (dlib-based)

---

## 📋 How to Run

### 1️⃣ Install dependencies
```bash
pip install opencv-python
pip install face-recognition
````

### 2️⃣ Run the script

```bash
python face_recognition.py
```

---

## 📄 Example Attendance Output

| Name  | Time        |
| ----- | ----------- |
| Alice | 09:05:12 AM |
| Bob   | 09:07:43 AM |

---

## 🙏 Acknowledgements

Inspired by the *Python Face Recognition & Attendance System* tutorial on YouTube.

---

## 📚 Notes

⚡ Ensure your camera is connected.
⚡ Keep clear, well-lit reference images in the `images/` folder.
⚡ The script does basic face matching and is ideal for small demos, not production use.

```
