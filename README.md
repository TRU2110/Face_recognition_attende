**Project Overview:** <br>
This project aimed to create a system that can automatically track attendance using facial recognition technology. Instead of traditional methods like taking roll calls, the system identifies individuals by their faces and records their attendance in a digital format.<br>

1] **Technology Used:** <br>
🔹 Python: Used as the main programming language for developing the system.<br>
🔹 OpenCV: A library used for handling video streams and image processing.<br>
🔹 face_recognition: A Python library that provides facial recognition capabilities, used to detect and recognize faces in images.<br>
🔹 CSV (Comma-Separated Values): Used to store and manage attendance data in a simple text format.<br>

2] **How It Works:** <br>
🔹  Face Detection: The system captures live video using a webcam and detects faces in each frame using OpenCV.<br>
🔹 Face Recognition: It then uses the face_recognition library to recognize faces by comparing them with pre-defined images of known individuals.<br>
🔹 Attendance Logging: When a recognized face matches a known face, the system logs the person's attendance in a CSV file along with the current date and time.<br>
🔹 Real-Time Processing: This process repeats continuously in real-time, allowing for efficient and accurate attendance tracking without manual intervention.<br>

3] **Benefits:** <br>
Automation: Eliminates the need for manual attendance taking, saving time and reducing errors.<br>
Accuracy: Provides reliable attendance records based on facial recognition technology.<br>
Efficiency: Streamlines the attendance tracking process for organizations and educational institutions.<br>
