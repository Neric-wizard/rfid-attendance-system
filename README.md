# 🎯 RFID Attendance Tracker

A **Smart RFID-Based Attendance Tracking System** that seamlessly integrates **Arduino hardware, Firebase Cloud Firestore**, and a **Java Swing desktop application** for real-time attendance monitoring and record management.  

This project demonstrates your ability to combine **IoT, Cloud, and Desktop development** into a fully functional system — ideal for academic, enterprise, or institutional use.

---

## ⚙️ Tech Stack

| Layer | Technology Used |
|-------|------------------|
| **Hardware** | Arduino UNO, MFRC522 RFID Reader, Buzzer, LCD Display |
| **Desktop App** | Java (Swing, JavaFX components), Serial Communication |
| **Cloud Backend** | Firebase Firestore |
| **Build Tool** | Gradle |
| **Version Control** | Git & GitHub |

---

## 💡 Features

- ✅ RFID-based student identification and attendance marking  
- ☁️ Real-time sync with Firebase Firestore  
- 🖥️ Elegant Java Swing UI with **Light/Dark Mode toggle**  
- 🕒 Live Clock Display on Dashboard  
- 📸 Student photo popup when RFID is scanned  
- 📊 Attendance export to CSV for reporting  
- 🔐 Secure serial communication with Arduino  
- 🔔 Visual & sound alerts on successful scans  

---

## 🧠 System Architecture

```
[RFID Tag] → [Arduino UNO + MFRC522] → [Serial Port] → [Java Desktop App] → [Firebase Firestore]
```

This architecture allows for **instant attendance updates** in the cloud as soon as a student’s RFID tag is scanned by the Arduino hardware.

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
- **Java JDK 17+**
- **Gradle** (or use included wrapper)
- **Arduino IDE** (for microcontroller setup)
- **Firebase Project** with Firestore database

### 2️⃣ Clone the Repository
```bash
git clone https://github.com/Neric-wizard/rfid-attendance-system.git
cd rfid-attendance-system
```

### 3️⃣ Add Firebase Credentials
Place your Firebase key JSON file here:
```
src/main/resources/serviceAccountKey.json
```

### 4️⃣ Run the Desktop App
```bash
./gradlew run
```

### 5️⃣ Connect the Arduino
- Upload the provided Arduino sketch.
- Note your serial port (e.g., `COM4`).
- Ensure your Java app uses the same port in the config.

---

## 📷 Screenshots

### 🪪 RFID Scan
![RFID Scan](https://github.com/user-attachments/assets/1e401041-f052-4bad-b009-649b1e86a6a0)

### 🖥️ Attendance Dashboard
![Dashboard](https://github.com/user-attachments/assets/c22f3cca-3a3f-471a-9f39-281c92f17c50)


## 🧑‍💻 Author

**👤 Njeck Neric**  
💼 Software Engineer | IoT & Cloud Enthusiast  
🌍 Buea, Cameroon  
🔗 [LinkedIn](https://linkedin.com/in/njeckneric)  
🐙 [GitHub](https://github.com/Neric-wizard)

---

## 🪪 License

This project is licensed under the **MIT License** – feel free to use and modify it for your learning or research.

---

> 💬 *“Innovative systems don’t just automate — they elevate efficiency.”*  
> — *Neric, Developer of RFID Attendance Tracker*
