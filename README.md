Face Recognition Attendance System

📌 Overview

This project is a Face Recognition-based Attendance System built using OpenCV and face_recognition. It automatically marks attendance by recognizing faces from a live webcam feed or pre-stored images.

🚀 Features

Real-time Face Detection using OpenCV

Face Recognition using face_recognition library

Automated Attendance Logging

CSV-based Attendance Records

Supports Multiple Users

🛠️ Tech Stack

Python 3.13

OpenCV (Computer Vision)

face_recognition (Face Detection & Recognition)

NumPy & Pandas (Data Processing)

📦 Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/rizulsharma-2003/Smart_Attendance_System.git
cd Smart_Attendance_System

2️⃣ Install Dependencies

Ensure you have pip installed, then run:

pip install -r requirements.txt

3️⃣ Run the Application

python face_recognition_system.py

🖼️ How It Works

Face Detection: The system detects faces in real-time using OpenCV.

Face Recognition: Matches detected faces with stored images.

Attendance Logging: If a recognized face matches a registered user, attendance is marked in a CSV file.

📂 Project Structure

Smart_Attendance_System/
│── data/                   # Stores user images
│── models/                 # Pre-trained face models
│── attendance.csv          # Attendance log file
│── face_recognition_system.py  # Main script
│── requirements.txt        # Dependencies
│── README.md               # Project documentation

🔥 Future Enhancements

Web-based UI for attendance management

Integration with databases (MySQL, Firebase)

Mobile App Support

📝 Author

👤 Rizul Sharma📧 write2rizul@gmail.com🔗 GitHub

📜 License

This project is licensed under the MIT License. Feel free to use and modify it! 🚀
