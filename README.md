🎯 RFID Attendance Tracker

A Smart RFID-Based Attendance Tracking System that seamlessly integrates Arduino hardware, Firebase Cloud Firestore, and a Java Swing desktop application for real-time attendance monitoring and record management.

This project showcases expertise in IoT, Cloud Systems, and Desktop Software Engineering — perfect for academic, enterprise, and institutional environments.

⚙️ Tech Stack
Layer	Technology Used
Hardware	Arduino UNO, MFRC522 RFID Reader, Buzzer, LCD Display
Desktop App	Java (Swing + JavaFX components), Serial Communication
Cloud Backend	Firebase Firestore
Build Tool	Gradle
Version Control	Git & GitHub
💡 Features

✅ RFID-based student identification & attendance logging

☁️ Real-time synchronization with Firebase Firestore

🖥️ Modern Java Swing UI with Light/Dark Mode

🕒 Live digital clock on dashboard

📸 Student photo popup upon successful scan

📊 Export attendance to CSV

🔐 Secure serial communication between Arduino & PC

🔔 Visual + buzzer feedback during scans

🧠 System Architecture
[RFID Tag] → [Arduino UNO + MFRC522] → [Serial Port] → [Java Desktop App] → [Firebase Firestore]


This ensures instant cloud updates immediately after an RFID tag is scanned.

🚀 Getting Started
1️⃣ Prerequisites

Java JDK 17+

Gradle (or the included gradlew wrapper)

Arduino IDE

Firebase project with Firestore enabled

2️⃣ Clone the Repository
git clone https://github.com/Neric-wizard/rfid-attendance-system.git
cd rfid-attendance-system

3️⃣ Add Firebase Credentials

Place your Firebase service account key here:

src/main/resources/serviceAccountKey.json

4️⃣ Run the Desktop Application
./gradlew run

5️⃣ Connect the Arduino

Upload the Arduino sketch from the repository

Identify your serial port (e.g., COM4)

Ensure the Java application uses the same port

📷 Screenshots
🪪 RFID Scan

🖥️ Attendance Dashboard

🧑‍💻 Author

👤 Njeck Neric
💼 Software Engineer — IoT, Cloud & Desktop Systems
🌍 Buea, Cameroon
🔗 LinkedIn

🐙 GitHub

🪪 License

Licensed under the MIT License.
You are free to use, modify, and build on this project.

💬 “Innovative systems don’t just automate — they elevate efficiency.”
— Njeck Neric
