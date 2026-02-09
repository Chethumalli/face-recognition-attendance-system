# 📸 Face Recognition Attendance System

An intelligent and interactive Python-based attendance system that automates the attendance process using real-time face detection and recognition. Built with a user-friendly GUI, this system captures, trains, and identifies faces to mark daily attendance accurately and efficiently. 
GitHub

## 🚀 Features

✨ Real-Time Face Detection & Recognition
The system uses OpenCV’s face detection and recognition techniques to capture and recognize faces from live webcam feed. 
GitHub

👤 User Registration
Easily register new individuals with unique IDs and names. Images are collected and stored for training. 
GitHub

📊 Automated Attendance Logging
Automatically creates and updates daily attendance CSV files with name, ID, date, and timestamp. 
GitHub

🛡️ Secure GUI With Authentication
Built using Tkinter to provide an intuitive and secure interface for users. 
GitHub

📁 CSV Reports
Attendance data is cleanly logged per day and can be opened in Excel or Google Sheets for further analysis. 
GitHub

## 🛠️ Tech Stack
<pre>
Component	Technology
Language	Python
GUI	Tkinter
Computer Vision	OpenCV
Data Storage	CSV files
Face Model	Haar Cascade + LBPH Face Recognizer
</pre>
 ## 🚀 How It Works

Training Dataset Creation

Capture multiple images per user using webcam.

Each face is stored with an ID and name. 
GitHub

Model Training

Train the LBPH face recognizer on saved images for accurate recognition. 
GitHub

Attendance Capture

System recognizes faces and logs attendance automatically with timestamp. 
GitHub

Report Generation

Daily CSV file is generated with full attendance details. 
GitHub

## 🧾 Installation

Clone the repository

git clone https://github.com/Chethumalli/face-recognition-attendance-system.git
cd face-recognition-attendance-system


Create Virtual Environment

python -m venv venv
source venv/bin/activate   # macOS / Linux
venv\Scripts\activate      # Windows


Install Dependencies

pip install -r requirements.txt


Run the App

python main.py

🧠 Recommended Workflow

✔ Register new faces first
✔ Train the model before marking attendance
✔ Use a well-lit environment for better recognition accuracy

## 📁 Directory Structure
<pre>
📦 face-recognition-attendance-system
 ┣ 📂 Attendance
 ┣ 📂 StudentDetails
 ┣ 📂 TrainingImage
 ┣ 📂 TrainingImageLabel
 ┣ 📜 main.py
 ┣ 📜 install commands .txt
 ┣ 📜 haarcascade_frontalface_default.xml
 ┣ 📜 README.md
 ┗ 📜 LICENSE
</pre>
📌 Notes

🔹 Works best with consistent lighting and clear face images.
🔹 For very large datasets or production deployment, consider using deep learning-based models (e.g., FaceNet, YOLO + FaceNet). 
GitHub

❤️ Contributions

Contributions that improve the accuracy, user interface, or architecture are welcome!

Fork the repository

Create your feature branch

Commit & push

Open a Pull Request

📄 License

This project is licensed under the MIT License — feel free to use and modify! 
GitHub
