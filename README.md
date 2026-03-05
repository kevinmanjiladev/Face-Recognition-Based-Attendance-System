

# Face Recognition Attendance System

A real-time **Face Recognition Attendance System** built using **Python, OpenCV, and Face Recognition library**.  
The system detects faces through a webcam, compares them with stored face encodings, and automatically records attendance with a timestamp.

---

## 🚀 Features

- Real-time face detection using webcam
- Face recognition using stored face encodings
- Automatic attendance marking
- Stores attendance with **name and timestamp**
- Prevents duplicate attendance entries
- Displays live video with bounding boxes and status messages

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV**
- **face_recognition**
- **NumPy**
- **CSV (for attendance storage)**

---

## 📂 Project Structure

```

Face-Recognition-Attendance-System/
│
├── images/                # Folder containing images of known faces
├── attendance.csv         # File where attendance is stored
├── main.py                # Main program
├── encodings.py           # Script to generate face encodings (optional)
└── README.md

````

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Face-Recognition-Attendance-System.git
cd Face-Recognition-Attendance-System
````

### 2. Install dependencies

```bash
pip install opencv-python
pip install face-recognition
pip install numpy
```

---

## ▶️ How It Works

1. The system loads images of known individuals.
2. Face encodings are generated for each image.
3. The webcam captures live video.
4. Detected faces are compared with known encodings.
5. If a match is found:

   * Attendance is marked
   * Name and timestamp are stored in `attendance.csv`
6. The system prevents duplicate entries for the same person.

---

## 📸 Example Output

```

Kevin, 2026-03-05 08:35:21
John, 2026-03-05 08:36:10

```

---

## 🔮 Future Improvements

* Store attendance in **SQL database**
* Add **multiple person attendance detection**
* Add **GUI interface**
* Deploy using **web application (Flask / Django)**
* Improve recognition accuracy with confidence thresholds

---

## 🙏 Acknowledgment

Special thanks to **Sabir K** for guidance and mentorship during this project.

---

## 📌 Author

**Kevin Manjila**

Interested in **Computer Vision, AI, and Machine Learning projects**.

```

---

✅ This README is **professional and good for GitHub + LinkedIn projects**.

If you want, I can also give you **3 things that make your GitHub project look 10× more professional**:

1. **Professional GitHub project structure**
2. **GIF demo of your system running**
3. **Project architecture diagram (very impressive for recruiters)**.
```
